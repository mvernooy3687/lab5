# lab5

Link to unit test from course's main project:
https://github.com/ECE444/Byte_Benevolence/blob/add_database/BBapp/database_unittest.py#L11

This entire branch was written by me; all ubit tests in database_unittest.py were written by me and all tests are currently passing.

Pros and cons of TDD:

Pros:
TDD forces the developer to define the problem in terms of the list of inputs required (which would be fed into the test) and how success is defined (this is forced through coding what conditions will make the test pass/fail). The answers to the above may not be entirely up to the developer or may raise questions, sparking further communication between the team/stakeholders to properly define the problem before sinking time into implementation. This helps avoid wasting time implementing, and then needing to change the implementation because of the goal of the code changing or being redefined.

Another pro is that defining the testing at the start means the developers will likely feel they can take their time when writing the tests. If tests are instead written just before a deadline when there is time pressure, there is an increased likelihood of mistakes, and less incentive to look for as many edge cases as possible.

Additionally, by writing tests first and taking your time, you will likely think about edge cases before implementing, meaning you will likely take into account edge cases while designing your implementation and therefore try to deal with them on your first pass as opposed to writing for the main cases then continually making fixes for each edge case.

Cons:
TDD requires time and effort upfront before getting to development. This can be difficult with a short and strict time to complete, especially because it delays implementation, meaning you will have to wait longer to get updated estimates of actual implementation time based on how the implementation is going.

TDD is effective when used from the start, but trying to adopt/apply TDD on legacy code can be difficult.

TDD requires effort to maintain the tests, especially as requirements change. This is code, time, and effort not spent on the actual features users experience.
