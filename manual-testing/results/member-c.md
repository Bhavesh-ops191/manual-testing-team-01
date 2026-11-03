# Manual Testing Results — Member C

## Environment

| Item | Details |
|---|---|
| Tester identifier | member-c |
| Date and time | 3/11/2026 2:57pm |
| Browser and version | Microsoft Edge 156 |
| Operating system | Windows 11 |

## Login Tests

### Test ID: LOGIN-N02

| Item | Details |
|---|---|
| Test type | Negative |
| Tester | member-c |
| Website | https://www.saucedemo.com/ |
| Status | Pass |

#### Purpose

Checks for a missing password.

#### Preconditions

Website is opened, input field are empty and user is logged out.

#### Test Data

| Field | Value |
|---|---|
| Name | standard_user |
| Password | Empty |

#### Steps

1. Follow the shared login procedure 
2. Enter the username.
3. Leave the password empty.
4. Select login.
5. Observe the feedback.

#### Expected Result

The attempt is rejected with validation feedback. The inventory is not reached.

#### Actual Result

Attempt is rejected with validation feedback stating "Password is required".

#### Evidence

[View screenshot](../evidence/member-c/login-n02.png)

---

## Equivalence Partitioning

### Test ID: AGE-EP-90-C

| Item | Details |
|---|---|
| Test type | Negative |
| Tester | member-c |
| Website | https://testpages.eviltester.com/apps/client-server-form-validation/submit |
| Status | Pass |

#### Purpose

Check if input of age 90 is rejected.

#### Preconditions

Website input form is opened and empty. 

#### Test Data

| Field | Value |
|---|---|
| First name | Alex |
| Surname	| TestingStudent |
| Age	| 90 |
| Country	| Afghanistan |
| Notes | Manual testing classroom exercise |

#### Steps

1. Restore the form.
2. Enter the valid baseline.
3. Change only age to 90.
5. Submit the form.
6. Observe acceptance or rejection.

#### Expected Result

Successful submission is prevented or a validation error is returned for the age input "90".

#### Actual Result

Validation error is returned with feedback "Value must be less than or equal to 80.".

#### Evidence

[View screenshot](../evidence/member-c/age-ep-90-C)

---

## 2-Point Boundary Tests

### Test ID: AGE-2P-80-C

| Item | Details |
|---|---|
| Test type | Positive |
| Tester | member-c |
| Website | https://testpages.eviltester.com/apps/client-server-form-validation/submit |
| Status | Pass |

#### Purpose

Check if input of age 80 is accepted.

#### Preconditions

Website input form is opened and empty. 

#### Test Data

| Field | Value |
|---|---|
| First name | Alex |
| Surname	| TestingStudent |
| Age	| 80 |
| Country	| Afghanistan |
| Notes | Manual testing classroom exercise |

#### Steps

1.Restores the form.
2. Enters the valid baseline.
3. Change only age to 80.
4. Submit the form.
5. Observe acceptance or rejection.

#### Expected Result

Form accepts input and successful submission of form.

#### Actual Result

Form accepts input and successful submission of form.

#### Evidence

Not captured

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