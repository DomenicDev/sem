

# USE CASE: 7 Update Details of Employee

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to update an employee's details* so that *employee's details are kept up-to-date*.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee.  Database contains employee.

### Success End Condition

Details of Employee are updated.

### Failed End Condition

Details of Employee are not updated.

### Primary Actor

HR Advisor.

### Trigger

A change request for an employee's details is received.

## MAIN SUCCESS SCENARIO

1. HR receives change request on an employee's details.
2. HR advisor views database record for given employee.
3. HR advisor applies the requested changes.
4. HR advisor provides confirmation to employee.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor gets in contact with requester.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
