# Backward Chaining Expert System

## About the Project

This project is a simple **Rule-Based Expert System** developed using Python.

It provides basic academic guidance for students using **Backward Chaining**.

## How It Works

The system starts with a goal and works backward to check whether the required facts are available.

For example:

```text
EligibleForPlacement
        ↓
GoodAttendance
GoodMarks
CompletedAssignments
        ↓
Goal is proved
```

## Facts

The system contains facts such as:

* GoodAttendance
* GoodMarks
* CompletedAssignments
* RegularPractice

## Rules

Some rules used in the system are:

* GoodAttendance + GoodMarks + CompletedAssignments → EligibleForPlacement
* GoodMarks + RegularPractice → GoodAcademicPerformance
* GoodAttendance + CompletedAssignments → NeedsExtraPractice
* EligibleForPlacement + RegularPractice → ReadyForInterview

## Algorithm Used

**Backward Chaining**

The program starts from the selected goal and checks the conditions needed to prove it.

## Technologies Used

* Python

## Sample Output

```text
BACKWARD CHAINING
-----------------
Goal: EligibleForPlacement

Reasoning Steps:
To prove EligibleForPlacement, checking:
GoodAttendance, GoodMarks, CompletedAssignments

Fact found: GoodAttendance
Fact found: GoodMarks
Fact found: CompletedAssignments
Rule satisfied: EligibleForPlacement

Final Conclusion:
EligibleForPlacement is proved.
```

## Conclusion

This project demonstrates how a simple expert system can use rules and facts to make decisions through backward chaining.
