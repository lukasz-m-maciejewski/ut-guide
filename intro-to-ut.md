# Welcome
## agenda
- purpose of unit tests
- given when then
- testing vs mocking
- google test features
- google mock features

---

# What unit tests are for
## while developing
- create controlled execution environment
- incrementally add behaviour
## when extending the system
- document expectated behavour
- prevent accidental change of behavour
- make extending the system safer

---

# Structure of a unit test
## Given ... when .. then ...
## Arrange Act Assert

---

# Test Framework vs Mocking Framework
## Test framework
Facititates grouping of tests and running them in a controlled environment. Provides fixtures for common initialization code. Provides assertions for expected results.
## Mocking framework
Facilitates creation of controllable interface implementations for mocking dependencies of a tested class.