unit testing // tests a class or multiple class
vs
integration testing //tests behavior of an external dependency
End-to-end test


dotnet restore //gets the NuGet package manager from .NET

Reference:
https://www.learnhowtoprogram.com/c-and-net/test-driven-development-with-c/mstest-configuration-quick-reference


Arrange gather, declare Class
Act   call the method 
Assert run test: arrange = act


GetType() method that returns data type of specific object
typeof returns data type of class
Assert.AreEqual(typeof(Item), newItem.GetType())

TEARDOWN METHOD 
// for static methods()
will reset instances of data for next test
IDisposable 
.Clear() removes items

[TestInitialize] runs before a test
[TestCleanup] runs after exicution of test--runs multiple times with multiple tests
