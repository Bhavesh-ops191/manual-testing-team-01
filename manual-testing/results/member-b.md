# Manual Testing Results — Member B

## Environment

| Item | Details |
|---|---|
| Tester identifier | member-b |
| Date and time | 03/11/2026 2:30PM |
| Browser and version | |
| Operating system | |

## Login Tests

### Test ID: LOGIN-N01

| Item | Details |
|---|---|
| Test type | Negative  |
| Tester | member-b |
| Website | https://www.saucedemo.com/ |
| Status | Pass |

#### Purpose

This test checks whether a user is able to log in with a incorrect password

#### Preconditions

username is valid

#### Test Data

| Field | Value |
|---|---|
| Username | standard_user |
| Password | wrong_password |

#### Steps

1. Open login page.
2. Enter the valid username.
3. Enter the incorrect password.
4. Select Login.
5. Observe the page and feedback

#### Expected Result

Website returns "Incorrect Password."

#### Actual Result

Website returned "Username and password do not match any user in this service."

#### Evidence

[View screenshot](../evidence/member-b/login-n01.png)

---

## Equivalence Partitioning

### Test ID: AGE-EP-10-B

| Item | Details |
|---|---|
| Test type | Negative |
| Tester | member-b |
| Website | https://testpages.eviltester.com/apps/client-server-form-validation/ |
| Status | Pass |

#### Purpose

This test checks whether the form will allow a submit if the age is below 18.

#### Preconditions

Firstname, Surname, Country and Notes must be valid.

#### Test Data

| Field | Value |
|---|---|
| Firstname | Alex |
| Surname | TestingStudent |
| Age | 10 |
| Country | Afghanistan |
| Notes | Manual testing classroom exercise |

#### Steps

1. Enter the valid Firstname, Surname, Country and Notes agreed among the team.
2. Change the Age to 10.
3. Submit.
4. Observe the results.

#### Expected Result

Website returns invalid age.

#### Actual Result

Website did not allow the submit due to the age being below 18.

#### Evidence

[View screenshot](../evidence/member-b/age-ep-10-b.png)

---

## 2-Point Boundary Tests

### Test ID: AGE-2P-18-B

| Item | Details |
|---|---|
| Test type | Positive |
| Tester | member-b |
| Website | https://testpages.eviltester.com/apps/client-server-form-validation/ |
| Status | pass |

#### Purpose

This test checks whether 18 is a valid age to submit the form.

#### Preconditions

Firstname, Surname, Country and Notes must be valid.

#### Test Data

| Field | Value |
|---|---|
| Firstname | Alex |
| Surname | TestingStudent |
| Age | 18 |
| Country | Afghanistan |
| Notes | Manual testing classroom exercise |

#### Steps

1. Enter the valid Firstname, Surname, Country and Notes agreed among the team.
2. Change the Age to 18.
3. Submit.
4. Observe the results.

#### Expected Result

Accepted since 18 is at the minimum age required.

#### Actual Result

Form submitted since 18 reaches the minimum age required.

#### Evidence

[View screenshot](../evidence/member-b/age-2p-18-b.png)

---

## 3-Point Boundary Tests

### Test ID: YOUR-TEST-ID

| Item | Details |
|---|---|
| Test type | Positive / Negative / Recovery |
| Tester | Your member identifier |
| Website | Website name |
| Status | Not run |

#### Purpose

What does this test check?

#### Preconditions

What must be true before the test starts?

#### Test Data

| Field | Value |
|---|---|
| Input name | Input value |

#### Steps

1.
2.
3.

#### Expected Result

Write this before executing the test.

#### Actual Result

Not recorded — test has not been executed.

#### Evidence

Not captured.

---