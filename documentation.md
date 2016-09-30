## How to make your own awesome list
```
mkdir awesome-<name>
cd awesome-<name>
touch readme.md
touch awesome-<name>.md
touch contributing.md
git init
git add .
git commit "First commit."
git remote add origin <github-url>
git push -u origin master
```

## How to set up npm markdown white space testing
```
npm init
mkdir tests
cd tests
touch whitespace_test.js
<copy paste whitespace test>
touch relaxed.json
<copy paste relaxed.json>
<copy paste markdownlint dependences>
cd ..
npm install
npm test
```

## A successful test run looks like
```➜  awesome-fam git:(master) npm test

> awesome-fam@1.0.0 test /Users/goat/lists/awesome-fam
> node tests/whitespace_test.js

Pass```
