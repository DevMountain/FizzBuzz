FizzBuzz
========

The sixth project for iOS pre-course using loops

### Resources:
- We're about to finish off (read section 4) "[Control Structures, Loops and Collections](http://codewithchris.com/how-to-make-iphone-apps-control-structures-loops-and-collections/)" intro to loops an d - Loops are pretty simple, and this article will give you a good overview.
- For Objective-C read RyPress.com's [C Basics](http://rypress.com/tutorials/objective-c/c-basics.html). Jump down to the section on Loops.
- For Swift read Apple's documentation on [For Loops](https://developer.apple.com/library/prerelease/mac/documentation/Swift/Conceptual/Swift_Programming_Language/ControlFlow.html#//apple_ref/doc/uid/TP40014097-CH9-XID_192)


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
- Example Output 1-100:

1
2
Buzz
4
Fizz
Buzz
7
8
Buzz
Fizz
11
Buzz
Buzz
14
FizzBuzz
16
17
Buzz
19
Fizz
Buzz
22
Buzz
Buzz
Fizz
26
Buzz
28
29
FizzBuzz
Buzz
Buzz
Buzz
Buzz
FizzBuzz
Buzz
Buzz
Buzz
Buzz
Fizz
41
Buzz
Buzz
44
FizzBuzz
46
47
Buzz
49
Fizz
FizzBuzz
Fizz
FizzBuzz
FizzBuzz
Fizz
Fizz
FizzBuzz
Fizz
Fizz
FizzBuzz
61
62
Buzz
64
Fizz
Buzz
67
68
Buzz
Fizz
71
Buzz
Buzz
74
FizzBuzz
76
77
Buzz
79
Fizz
Buzz
82
Buzz
Buzz
Fizz
86
Buzz
88
89
FizzBuzz
91
92
Buzz
94
Fizz
Buzz
97
98
Buzz
Fizz
