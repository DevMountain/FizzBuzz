FizzBuzz
========

The sixth project for iOS pre-course using loops

### Resources:

### Step 1: Get the project started on your computer and on GitHub
- Either create a project locally and push to GitHub
- Or fork this project and clone it to your computer

*Note:*
- *For more detailed instructions of 'Step 1' see the first [project](https://github.com/DevMountain/AGoodStart.git)*
- *'Step 1' is something we will do hundreds of times in class. You need to be able to do it quickly and without running into issues so it doesn't slow class down.*


### Step 2: Create a buzz check method
- Add a method called isBuzzed that takes an integer and returns a bool
- The method should check to see if the integer is a multiple of 3
- If the number is a multiple of 3 it should return true
- If the number is not a multiple of 3 the method should check to see if the number contains the character 3
- If the number contains the character three it should return true
- Otherwise it should return false

### Step 3: Create a fizz check method
- Add a method called isFizzed that takes an integer and returns a bool
- The method should check to see if the integer is a multiple of 5
- If the number is a multiple of 5 it should return true
- If the number is not a multiple of 5 the method should check to see if the number contains the character 5
- If the number contains the character three it should return true
- Otherwise it should return false

### Step 4: Call FizzBuzz methods
- In your didFinishLaunching method loop through numbers 1-100
- For each integer call isBuzzed and isFizzed
- If the integer isBuzzed but not isFizzed print "Buzz"
- If the integer isFizzed but not isBuzzed print "Fizz"
- If the integer isFizzed and isBuzzed print "FizzBuzz"
- If the integer is not isFizzed and is not isBuzzed print the number

### Completion
- You should have printed numbers 1-100.
- You shouldn't see any 3s or 5s in the list anywhere. 
- You could start by looking at 6, 9, 12 and see if they are buzzed
- You could look at 5, 10, 25, 95 and see if they are fizzed
- You could look at 15, 51, 90 and see if they are fizzbuzzed
