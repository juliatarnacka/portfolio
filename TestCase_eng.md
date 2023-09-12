# Test case template 
**TEST - _Test title_**

**TEST ENVIRONMENT**

**TEST APPS AND DEVICES**

**TEST CONDITIONS**

**TEST DATA**

**TEST STEPS**

**EXPECTED RESULT**

**ACTUAL RESULT**

**SUMMARY**

**TEST RESULT**

**ATTACHEMENTS**


#Example test case based on https://szkolawchmurze.org/

1. Test - searching bar
2. Test environment - https://szkolawchmurze.org/blog
3. Test Devices and Apps: Macbook Pro, Chrome: Version 116.0.5845.179
4. Test conditions: Search term: "Odkładanie", "Odkładanie wszystkiego na póżniej - o prokrastynacji", "później"
5. Test Steps:


1. Go to the website "https://szkolawchmurze.org/blog"

2. Go to the search box and type "Odkładanie wszystkiego na póżniej - o prokrastynacji"

6.Expected result: After entering the test data, the page displaying the article "Odkładanie wszystkiego na póżniej - o prokrastynacji"


7. Actual result:
TC1 - Search for "Odkładanie wszystkiego na póżniej - o prokrastynacji"

The page displaying the article "Odkładanie wszystkiego na póżniej - o prokrastynacji"

TC2 - Search for "Odkładanie"

The page displaying the article "Odkładanie wszystkiego na póżniej - o prokrastynacji"

TC3 - Search for "Odkładanie wszystkiego na póżniej - o prokrastynacji" in capital letters only

The page displaying the article "Odkładanie wszystkiego na póżniej - o prokrastynacji"

TC4 - Search for "później"

The page displaying the article "Odkładanie wszystkiego na póżniej - o prokrastynacji"

8. Summary - search for "Odkładanie", "Odkładanie wszystkiego na póżniej - o prokrastynacji", and "później" according to the expected result.

9. Test Result: Passed.
