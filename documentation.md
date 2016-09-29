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
