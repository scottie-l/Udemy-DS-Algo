# Problem Solving

What's an Algorithm? A process or set of steps to accomplish a certain task. Almost everyhtiong that you do in programming involves some kind of algorithm. It's the foundation for being a sucessful problem solving and developer.

How do you improve?

1. Devise a plan for solving problems
2. Master common problem solving patterns

### Problme Solving Strategies -

- Understand the problem
- Explore Concrete examples
- Break it down
- Solve/Simplify
- Look back and refactor

- Understand the problem
    - Can you restate teh problem in your own words?
    - What are the inputs that go into the problem?
    - What are the outputs that go into the problem?
    - Can the outputs be determined form the inputs? (Do you have enough information to solve the problem? You may or may not until further in problem.)
    - How should I label the important pieces of data that are a part of the problem?

Example: Write a function which takwes 2 numbers and returns their sum.

1. Can I restate the problem in own words? Add 2 numbers
2. What are the inputs that go into the problem? String, Integer, Boolean. Is there an upper limit to input.
3. What are the outputs that should come from the solution? String, Integer, Boolean, Float.
4. Can the outputs be determined from the inputs? Is a string, Integer, Boolean. Ask about outputs.
5. How should I label the important pieces of data that are part of the problem? Sum, Total num1, num2. What are the descriptive names of varialbes.

- Explore Concrete Examples
    - Can help you to understand problem better.
    - Examples provide sanity checks that your eventual solution works how it should.
        - User Stories or Unit tests.

1. Start with simple examples.
2. Progress to more complex examples.
3. Explore Examples with empty inputs.
4. Explore Examples with invalid inputs.

Example: Write a function which takes in a string and returns counts of each character in the string.

1. charCount('aaaa'); {a:4, b:0, c:0} Should count 4 a's. But what about b, or c, etc
2. charcount('hello'); {h:1, e:1, l:2, o:1} Are capitals counted?
3. Input - 'My phone number is 182763'. Do we acccount for spaces, integers and characters?
4. charCount(); Do we want null, undefined, empty string.

- Break it Down
    - Explicitly write out the steps you need to take.

Example: Write a function which takes in a string and returns counts of each character in the string.

1. make object to return object at end
2. loop over string
    3. if the char is a number/letter AND is a key in the object, add one to the count
    4. if the char is a number/letter AND is not in the object, add it to the object and set value to 1.
    5. if char is something else (period, space, etc.) don't do anything.
6. return object

- Solve/Simplify
    - If you can't solve, move to simpler part that you can solve.
    - You may gain insight from the simpler problem.

1. Find the core difficulty in waht you're tryin to do.
2. Temporarily ignore that difficulty
3. Write a simplified solution.
4. Then  incorporate that difficulty back in.

Example: Write a function which takes in a string and returns counts of each character in the string.

- if you have trouble looping, start with one character

- Look back and refactor
    - 
    
