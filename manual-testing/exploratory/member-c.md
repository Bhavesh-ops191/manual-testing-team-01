# Self-Designed Testing — Member C

## Testing Idea 1

I want to test if the website is able to successfully complete checkout.

## Reason

Check that users are able to order items from the website after providing the neccesary details.

## Test Basis

What requirement or stated expectation am I checking?
Check if users are able to complete checkout with an item after providing all the needed details.

Record any assumptions or unclear requirements.
Assume that payment details is already recorded and stored on the website, and has enough money to purchase the item.

## Approach

How will I choose data and perform the tests?
Data from previous tests of when a user is logged into the account will be used to test the functionality of the website.

## Test Cases

### Test ID: OWN-PT1-C-03

| Item | Details |
|---|---|
| Test type | Positive |
| Tester | member-c |
| Status | Pass |

#### Purpose

This test checks if a user is able to check out after adding an item to cart

#### Preconditions

User is logged in and at least 1 item has been added to cart

#### Test Data

| Field | Value |
|---|---|
| First name | Test |
| Last Name	| User |
| Postal Code | 123456 |

#### Steps

1. Click "Checkout"
2. Enter test data into the fields on the "Checkout: Your Information" page
3. Click "Continue"
4. Check order details on "Checkout: Overview" page and click "Finish"
5. Observe acceptance or rejection.

#### Expected Result

User should be able to finish checking out with a confirmation page of the order displayed.

#### Actual Result

A confirmation page of the order is displayed with an option to save a pdf of the order or return to home.

#### Evidence

Not captured.

---

## Overall Observations

User is able to finish checking out and save a pdf of the invoice.

## Next Question

What would I investigate next?
Will I be able to complete check out if I have no items added to cart?

