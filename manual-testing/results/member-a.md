# Manual Testing Results — Member A

## Environment

| Item | Details |
|---|---|
| Tester identifier | member-a |
| Date and time | |
| Browser and version | |
| Operating system | |

## Login Tests
### Test ID: LOGIN-P01

| Item | Details |
|---|---|
| Test type | Positive |
| Tester | Member A |
| Website | https://www.saucedemo.com/ |
| Status | Pass |

#### Purpose

To test valid login credentials

#### Preconditions

Both username and password must be true.

#### Test Data

| Field | Value |
|---|---|
| Username | standard_user |
| Password | secret_sauce |

#### Steps

1. Follow the shared starting procedure.
2. Enter the username.
3. Enter the password.
4. Select Login.
5. Observe the page reached.
6. Check that products are visible.

#### Expected Result

The inventory page appears and products are visible.

#### Actual Result

The inventory page appears and products are visible.

#### Evidence

[View screenshot](../evidence/member-a/login-p01.png)

---

## Equivalence Partitioning
### Test ID: AGE-EP-30-A

| Item | Details |
|---|---|
| Test type | Positive |
| Tester | Member A |
| Website | https://testpages.eviltester.com/apps/client-server-form-validation/ |
| Status | Fail |

#### Purpose

To test if inclusive ages are working as intended.

#### Preconditions

Age must be inclusive.

#### Test Data

| Field | Value |
|---|---|
| Firstname | Alex |
| Lastname | TestingStudent |
| Age | 30 |
| Country | Afghanistan |
| Notes | Manual testing classroom exercise |

#### Steps

1. Restore the form.
2. Enter the valid baseline.
3. Change only age.
4. Write the expected result.
5. Submit.
6. Observe acceptance or rejection.
7. Where displayed, verify the submitted age.
8. Record the actual result and status in a separate test-case block.

#### Expected Result

The submission goes through.

#### Actual Result

The firstname is too short.

#### Evidence

[View screenshot](../evidence/member-a/age-ep-30.png)

---

## 2-Point Boundary Tests

## 3-Point Boundary Tests