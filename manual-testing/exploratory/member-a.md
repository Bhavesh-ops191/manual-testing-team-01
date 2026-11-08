# Self-Designed Testing — Member A

## Testing Idea

What do I want to investigate?

I want to test if wrong username affects the login

## Reason

Why is this worth testing?

if somehow some way there is same passwords in the database, with no specifications on username, what if it login into the wrong account?

## Test Basis

What requirement or stated expectation am I checking?

Requirements will be same as the earlier examples, but use a wrong username.

Record any assumptions or unclear requirements.

## Approach

How will I choose data and perform the tests?

I will use the data from earlier examples, but use a wrong username.

## Test Cases

### Test ID: OWN-A-01

| Item | Details |
|---|---|
| Test type | Exploratory |
| Tester | member-a |
| Status | Pass |

#### Purpose

What does this individual test check?

if wrong username affects the login

#### Preconditions

What starting state is required?

all values be inputed, with wrong username

#### Test Data

| Field | Value |
|---|---|
| Username | standard |
| Password | secret_sauce |

#### Steps

1.
2.
3.

#### Expected Result

Failed login

#### Actual Result

Failed login

#### Evidence

[View screenshot](../evidence/member-a/own.png)

---

## Overall Observations

What did the tests show?

wrong username will make login fail.

## Next Question

What would I investigate next?

nil