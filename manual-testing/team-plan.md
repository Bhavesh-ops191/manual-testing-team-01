# Team Plan

## Team Identifier

## Members

### Member A
- GitHub username: GohYongZe
- Coordination responsibility: Team Coordination

### Member B
- GitHub username: ky194
- Coordination responsibility: Requirements and Baseline

### Member C
- GitHub username: xueeuee
- Coordination responsibility: Guided Test Coverage

### Member D
- GitHub username: Bhavesh-ops191
- Coordination responsibility: Evidence Organisation

### Member E
- GitHub username: Gerick Yi WeiZhao
- Coordination responsibility: Repository Integration

## Guided Test Allocation

| Member | Test ID |	Scenario |
|---|---|---|
| A	| LOGIN-P01 |	Valid credentials |
| B	| LOGIN-N01	| Incorrect password |
| C	| LOGIN-N02	| Missing password |
| D	| LOGIN-N03	| Missing username |
| E |	LOGIN-R01	| Correct an invalid attempt |

| Member | Test ID | Task |
|---|---|---|
| A | AGE-EP-30-A | Test age 30 |
| B	| AGE-EP-10-B | Test age 10 |
| C	| AGE-EP-90-C | Test age 90 |
| D	| AGE-EP-D | Observe blank age handling |
| E	| AGE-EP-ABC-E | Observe non-numeric input handling using abc |

| Member | Test ID | Assigned age |
|---|---|---|
| A	| AGE-2P-17-A | 17 |
| B | AGE-2P-18-B | 18 |
| C	| AGE-2P-80-C | 80 |
| D | AGE-2P-81-D| 81 |
| E	| AGE-2P-81-E | Independently repeat 18 and 81 |

| Member | Test ID | Additional age |
|---|---|---|
| A	| AGE-3P-16-A | 16 |
| B | AGE-3P-19-B | 19 |
| C	| AGE-3P-79-C | 79 |
| D | AGE-3P-82-D| 82 |
| E	| AGE-3P-82-E | Independently repeat 16 and 82 |

## Agreed Baseline Data
| Field | Baseline value |
| -- | -- |
| First name | Alex |
| Surname	| TestingStudent |
| Age	| 30 |
| Country	| Afghanistan |
| Notes | Manual testing classroom exercise |

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

[View screenshot](./evidence/member-a/age-ep-30.png)

---

## Open-Ended Testing Allocation
### Member A — Open-Ended Testing

- Chosen area: Positive and Negative Login Testing
- Question to investigate: what if username is wrong?

### Member B — Open-Ended Testing

### Member C — Open-Ended Testing

- Chosen area: Positive and Negative Checkout
- Question to investigate: Can a user complete checkout?

### Member D — Open-Ended Testing

### Member E — Open-Ended Testing

## Repository Integration Arrangements