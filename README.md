TypeScript React Multi-Check Testing Program
============================================

## Notice:

This is a simplified component from real project.
When you do it, consider it as a real task, and show your best programming practices.
Your code will be reviewed and scored by the other developers of the team you will join.

Your code will have higher score if:

1. The code is clean and easy to read and understand
2. The variable and function names are considered carefully
3. Small and meaning functions for complex logic
4. No typo and has good code format
5. Meaningful, carefully organized test cases covered most of the important functionality
6. Proper comments when it's necessary

## Task

Implement a react function component with typescript.

1. typescript + react
2. unit tests: use `jest`
3. write proper comments in code
4. show your best practise
5. use github pull request to submit your code

Find `TODO` in code to implement, you can also change any code in codebase to make it better.

## Component Requirement:

![demo](./images/demo.png)

1. The label of the component
2. The special `Select All` option
   1. if checked, all other options are checked
   2. if unchecked, all other options are unchecked
   3. if all other options are checked, it should be checked
   4. if any other option are unchecked, it should be unchecked
3. The options direction is from top to bottom

## Dev

```
npm install
npm run dev
```

## Test

```
npm test
```

Notice:
1. Tests of `App.tsx` is not required
2. Only need to test `MultiCheck.tsx`
3. Please follow best Typescript style and best practices
