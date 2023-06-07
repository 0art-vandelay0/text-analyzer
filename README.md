## **Unit Tests**

### **_Block_**

Describe: wordCounter()

#### **Test 1**

Test: "It should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output: 1

#### **Test 2**

Test: "It should return 2 if a passage has two words."
Code:
const text = "hello there";
wordCounter(text);
Expected Output: 2

#### **Test 3**

Test: "It should return 0 for an empty string."
Code:
wordCounter("");
Expected Output: 0

#### **Test 4**

Test: "It should return 0 for a string that is only spaces."
Code: wordCounter(" ");
Expected Output: 0

#### **Test 5**

Test: "It should not count numbers as words."
Code: wordCounter("hi there 77 19");
Expected Output: 2
