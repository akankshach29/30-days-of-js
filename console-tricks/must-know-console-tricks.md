1. Basic -
    console.log(‘Akanksha’)

    console output-  
    Akanksha

2. Interpolation -
    console.log(‘I am a %s developer’, ‘full stack web’)

    console output- 
    I am a full stack web developer

3. Styling -
    console.log('%c I am text', 'font-size:18px; color:red;')

    console output-
    I am text

4. Warnings - 
    console.warn(‘this is a warning!’)

    console output -
    this is a warning!

5. Error -
    console.error(‘Shit! An error occurred.’)

    console output -
    Shit! An error occurred.

6. Testing - This tests for a false statement. If a statement is true, it won’t console anything.
    console.assert(2 === 1, 'That is incorrect!');

    console output -
    Assertion failed. That is incorrect!

7. Clearing - This clears your console.
    console.clear();

    Console output -
    console was cleared
     
8. Table - 
     const person=[{name: 'Paul', age: 27}, {name: 'Missie', age: 12}];
     console.table(person)

     console output - 
     


9. Grouping Together -
    const person=[{name: 'Paul', age: 27}, {name: 'Missie', age: 12}];

    // without grouping
    person.forEach(eachPerson => { 
console.log(`this is ${eachPerson.name}`); 
console.log(`${eachPerson.name} is ${eachPerson.age} years old`);
    });

    console output -
    
     // when grouped together
     person.forEach(eachPerson => {
console.groupCollapsed(`${eachPerson.name}`);
     	console.log(`this is ${eachPerson.name}`);
console.log(`${eachPerson.name} is ${eachPerson.age} years old`);
console.groupEnd(`${eachPerson.name}`);
    });

    console output - 
    

     

10. Counting - 
      console.count('Paul')
      console.count('Paul')
      console.count('Paul')
 
     console output - 
     

      console.count('Paul')
      console.count('Paul')
      console.count('Paul')
      console.count('Akanksha')
      console.count('Paul')
      console.count('Akanksha')

     console output - 
     

11. Timing - It tells how long it is taking to fetch data from somewhere.
      console.time('fetching data');
      fetch('https://api.github.com/users/akankshach29')
  	.then(data => data.json())
.then(data => {
console.timeEnd('fetching data');
console.log(data);
});

    console output -
    
