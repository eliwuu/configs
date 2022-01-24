npm install --save-dev mocha chai ts-node @types/mocha @types/chai

"scripts": {
"test": "mocha -r ts-node/register test/\*.test.ts",
}
