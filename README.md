# DynamoDB Toolbox Type Inference Test

This project provides an example for DynamoDB Toolbox issue [#261](https://github.com/jeremydaly/dynamodb-toolbox/issues/261).

This project is derived from the Goldstack [DynamoDB Template](https://goldstack.party/templates/dynamodb).

## Steps to reproduce issue

- Clone project
- Ensure Yarn installed locally
- Run `yarn && yarn build`
- Open in VSCode and navigate to file `packages\dynamodb\src\table.spec.ts`
- Choose to use TypeScript version configured in workspace
- Hover over `{ Item: user } ` in line 68 of the file