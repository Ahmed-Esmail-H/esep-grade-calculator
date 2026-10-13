# ESEP Grade Calculator

This is a simple Go library that computes a student's final letter grade from assignments, exams, and essays.

Runtime requirements:
Go 1.24+

Project layout
|--README.MD
|--grade-calculator/
    |--go.mod
    |--grade_calculator.go
    |--grade_calculatortest.go

Run unit tests:

Run from inside `grade-calculator/`:
```
go test ./...          # run all tests
go test -v ./...       # show each test by name
go test -run TestGetGradeA ./...   # run a single test
```

Run unit tests with code coverage:
```
go test -cover ./...
go test -coverprofile=coverage.txt ./...
```