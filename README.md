# LOKESH 
git init
echo "function greet() { console.log('Hello World'); }" > App.js
git add App.js
git commit -m "Initial commit with greet()"
function greet() {
  console.log('Hello World');
}
git branch feature1
git branch feature2
git checkout feature1
function greet() {
  console.log('Hello from Feature 1');
}
git add App.js
git commit -m "Feature1: changed greeting message"
git checkout feature2
function greet() {
  console.log('Hello from Feature 2');
}
git add App.js
git commit -m "Feature2: changed greeting message"
git checkout main
git merge feature1
git merge feature2
function greet() {
  console.log('Hello from both features!');
}
git add App.js
git commit -m "Resolved merge conflict between feature1 and feature2"
