
#java-exception
Java project created via STS as Java Project
- created Checked Exceptions (MyException1, MyException2, MyException1Child), 
- created Checked Exceptions that are child of other Checked Exception (MyException1Child),
- threw checked Exceptions (Main.method1), 
- handled checked Exceptions thrown by called methods via either try/catch or throws (MyMain.useMethod1,2,3,4,5), 
- checked Exception inheritance, used in overwriting methods in Child classes that throws these Exceptions,
- wrapped an Exception into another Exception (via its constructor that takes a Throwable) and threw that
