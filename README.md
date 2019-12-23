Leap
Write a program that will take a year and report if it is a leap year.
The tricky thing here is that a leap year in the Gregorian calendar occurs:
on every year that is evenly divisible by 4
  except every year that is evenly divisible by 100
    unless the year is also evenly divisible by 400

For example, 1997 is not a leap year, but 1996 is. 1900 is not a leap year, but 2000 is.
If your language provides a method in the standard library that does this look-up, pretend it doesn't exist and implement it yourself.

Writing the Code
Execute the tests with:

$ cargo test

All but the first test have been ignored. After you get the first test to pass, remove the ignore flag (#[ignore]) from the next test and get the tests to pass again. The test file is located in the tests directory. You can also remove the ignore flag from all the tests to get them to run all at once if you wish.
Make sure to read the Crates and Modules chapter if you haven't already, it will help you with organizing your files.
