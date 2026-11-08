1. What makes a test positive or negative?
A test is positive if the system is able to work as expected and a negative test is when the system successfully carries out rejection validation and throws an error where expected.

2. Why can a negative test pass?
A negative test can pass if its expected output is to give a failed/rejected outcome.

3. How did equivalence partitioning help you select data?
It reduces the number of test cases needed to check the outcome of values in a range of values. Equivalence partitioning ensures that all values being tested best represents the behaviour of each partition in the valid and invalid range of values that results in the same outcome.

For example, if numbers between 10 and 20 are accepted, data that should be tested are 9, 15 and 21. 9 and 21 is out of the valid range of numbers which should result in a validation error and be rejected. 15 should be a valid value and accepted by the system.

4. What did boundary testing help you investigate?
Boundary testing allows us to test values next to extreme values and verify if the system is able to handle the valid values and reject invalid values. 

For example, if the extreme value that a system accepts is any input <80, the boundary values to be tested are 79 and 81, where 79 should be accepted by the system and 81 is rejected.

5. What did you choose to test during the open-ended activity, and why?
I chose to check the checkout system on the Swag Labs website for when a user adds an item to cart and wants to finish checking out. This is so that users are able to use the features on the website, which is for ordering items on an online shopping platform, after successfully logging in.

6. Did your observations lead to follow-up tests?
Yes. After testing a positive test case of a user checking out an order on the website, I tested for a negative test case where the user checks out with no items added to cart to check if a validation error is successfully thrown.

7. How does your Git history show your contribution?
It shows each part of the individual tests I have done for every commit I have made. Each instance of a change can be easily found if there is a specific test that the team wants to identify and check the details of.
