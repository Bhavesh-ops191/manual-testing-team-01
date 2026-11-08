# Self-Designed Testing — Member E

## Testing Idea

What do I want to investigate?
If capitalization of the first and last name matters in the details of the input form  
## Reason

Why is this worth testing?
To test if the system stores input as-is or automatically capitalize the frist and last name before displaying the information to the user
## Test Basis

What requirement or stated expectation am I checking?
The system shall reject valid alphabetical characters for first and last name fields without case-dependent rejection
Record any assumptions or unclear requirements.
Name validation is assumed to be case-sensitive unless specifically designated as a case-insensitive credential
## Approach

How will I choose data and perform the tests?
Baseline data with only changes in the capitalization of letters in the first and last name section.
## Test Cases

### Test ID: OWN-E-01

| Item | Details |
|---|---|
| Test type | Negative |
| Website | https://testpages.eviltester.com/apps/client-server-form-validation/ |
| Tester | member-e |
| Status | Fail |

#### Purpose

What does this individual test check?
Verify whether the form enforces capitalization requirements on the Surname field by checking if submitting an all-lowercase surname triggers a error message or is accepted.

#### Preconditions

What starting state is required?
The validation form is open.
All other fields will use the agreed valid baseline.

#### Test Data

| Field | Value |
| Firstname | Alex |
| Lastname | testingstudent |
| Age | 30 |
| Country | Afghanistan |
| Notes | Manual testing classroom exercise |

#### Steps

1. Restore the form.
2. Enter the valid baseline.
3. Change only the uppercase letters in Surname to lowercase.
4. Write the expected result.
5. Submit.
6. Observe acceptance or rejection.
7. Where displayed, verify the submitted name.
8. Record the actual result and status in a separate test-case block.

#### Expected Result

State the expected behaviour and its basis.

If the behaviour is unspecified, record the question being investigated.

Error message that indicates that the first letter of the Surname must be capitalized
#### Actual Result

No error message for the fully lower cased Surname only message of too short Firstname

#### Evidence

[View screenshot](..\evidence\member-e\login-OWN-E-01.png)

---

## Overall Observations

What did the tests show?
It does not force a uppercase constraint on the Surname, permitting lowercase surnames
## Next Question

What would I investigate next?
Does the Firstname field also accept an all-lowercase entry, or does it enforce different capitalization rules than the Surname field?

### Test ID: OWN-E-02

| Item | Details |
|---|---|
| Test type | Negative |
| Website | https://testpages.eviltester.com/apps/client-server-form-validation/ |
| Tester | member-e |
| Status | Fail |

#### Purpose

What does this individual test check?
Verify whether the form enforces capitalization requirements on the Firstname field by checking if submitting an all-lowercase firstname triggers a error message or is accepted.

#### Preconditions

What starting state is required?
The validation form is open.
All other fields will use the agreed valid baseline.

#### Test Data

| Field | Value |
| Firstname | alex |
| Lastname | TestingStudent |
| Age | 30 |
| Country | Afghanistan |
| Notes | Manual testing classroom exercise |

#### Steps

1. Restore the form.
2. Enter the valid baseline.
3. Change only the uppercase letters in Firstname to lowercase.
4. Write the expected result.
5. Submit.
6. Observe acceptance or rejection.
7. Where displayed, verify the submitted name.
8. Record the actual result and status in a separate test-case block.

#### Expected Result

State the expected behaviour and its basis.

If the behaviour is unspecified, record the question being investigated.

Error message that indicates that the first letter of the Firstname must be capitalized
#### Actual Result

No error message for the fully lower cased Firstname only message of too short Firstname

#### Evidence

[View screenshot](..\evidence\member-e\login-OWN-E-02.png)

---

## Overall Observations

What did the tests show?
It does not force a uppercase constraint on the firstname and surname, permitting lowercase full names
## Next Question

What would I investigate next?
NIL