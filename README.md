Instructions from Manuel:

## Running the Tests

 The way it works is that the test framework is a separate foundry module.
 
 To use it you'll need to load both socketlib and socketlib-test into the same world and connect 4 browsers into it (2 GM, 2 player).
 
 Then open the console in one of the GM-Browsers and execute `socketlibTest.run()`.
 
 All tests will then be exectuted and the console log reports whether the tests have been successful.

### Failed Tests

The test framework also triggers cases that are supposed to lead to an error and those errors will show up in the foundry GUI and the console.

This doesn't necessarily mean that a test failed.

Some tests expect errors to happen.

Whether a test is successful is indicated by separate console outputs.
