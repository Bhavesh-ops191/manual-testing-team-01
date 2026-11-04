# Manual Testing Results — Member E

## Environment

| Item | Details |
|---|---|
| Tester identifier | Member-E |
| Date and time |03/11/2026 |
| Browser and version |Firefox Ver 159.0|
| Operating system |Windows|

## Login Tests
### Test ID: LOGIN-R01

| Item | Details |
|---|---|
| Test type | Recovery  |
| Tester | Member-E |
| Website | https://www.saucedemo.com/ |
| Status | Pass |

#### Purpose

What does this test check?
If recovery after an invalid attempt is possible

#### Preconditions

What must be true before the test starts?
username and password must exist

#### Test Data

| Field | Value |
|username|standard_user|
|password|wrong_password|
|password|secret_sauce|

#### Steps

1. Follow the shared starting procedure.
2. Enter standard_user and wrong_password.
3. Select Login.
4. Confirm rejection.
5. Replace the password with secret_sauce.
6. Keep the username unchanged.
7. Select Login again.
8. Check whether the inventory appears.

#### Expected Result

Error message that specifies what is causing the error, password or username

#### Actual Result

Login displays error message which whenever there is a login issue and will disappear when the username or password is changed

#### Evidence

[View screenshot](..\evidence\member-e\login-R01.png)


## Equivalence Partitioning
| Item | Details |
|---|---|
| Test type | Negative |
| Tester | Member-E |
| Website | https://testpages.eviltester.com/apps/client-server-form-validation/ |
| Status | Pass |

#### Purpose

What does this test check?
If entering invalid credentials will cause a rejection in submission of data

#### Preconditions

What must be true before the test starts?
The validation form is open.
All other fields will use the agreed valid baseline.

#### Test Data

| Field | Value |
| Firstname | Alex |
| Lastname | TestingStudent |
| Age | abc |
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

Error message that indicates that the age can only have numbers

#### Actual Result

Error message at the age box stating that a number must be entered

#### Evidence

[View screenshot](..\evidence\member-e\login-AGE-EP-abc-E.png)

## 2-Point Boundary Tests
### Test ID: AGE-2P-18-E

| Item | Details |
|---|---|
| Test type | Positive |
| Tester | member-e |
| Website | Test Pages validation form |
| Technique | 2-point boundary testing |
| Status | Pass |

#### Purpose

Check that age the minimum is accepted.

#### Preconditions

The validation form is open.
All other fields will use the agreed valid baseline.

#### Test Data

| Field | Value |
|---|---|
| Age | `18` |
| Other fields | Agreed valid baseline |

#### Steps

1. Restore the validation form.
2. Enter the agreed baseline.
3. Replace age with `18`.
4. Submit.
5. Observe the response.

#### Expected Result

Age 18 is accepted because it is the minimum age of 18.

#### Actual Result

Age 18 is accepted because it is the minimum age of 18.

#### Evidence

[View screenshot](..evidence\member-e\login-AGE-2P-18-E.png)

---

### Test ID: AGE-2P-81-E

| Item | Details |
|---|---|
| Test type | Negative |
| Tester | member-e |
| Website | Test Pages validation form |
| Technique | 2-point boundary testing |
| Status | Pass |

#### Purpose

Check that an age immediately above the maximum is rejected.

#### Preconditions

The validation form is open.
All other fields will use the agreed valid baseline.

#### Test Data

| Field | Value |
|---|---|
| Age | `81` |
| Other fields | Agreed valid baseline |

#### Steps

1. Restore the validation form.
2. Enter the agreed baseline.
3. Replace age with `81`.
4. Submit.
5. Observe the response.

#### Expected Result

Age 81 is rejected because it is above the maximum age of 80.

#### Actual Result

Age 81 is rejected because it is above the maximum age of 80.

#### Evidence

[View screenshot](..evidence\member-e\login-AGE-2P-81-E.png)

---

## 3-Point Boundary Tests