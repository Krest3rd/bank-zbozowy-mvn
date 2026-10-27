# bank-zbozowy-mvn

## Zadanie 5
### 5.
```
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running put.io.selenium.atm.AtmCardInfoTest
[INFO] Tests run: 6, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.030 s -- in put.io.selenium.atm.AtmCardInfoTest
[INFO] 
[INFO] Results:
[INFO] 
[INFO] Tests run: 6, Failures: 0, Errors: 0, Skipped: 0
[INFO] 
[INFO] 
[INFO] --- war:3.5.1:war (default-war) @ BankZbozowyApp ---
[INFO] Packaging webapp
[INFO] Assembling webapp [BankZbozowyApp] in [/home/runner/work/bank-zbozowy-mvn/bank-zbozowy-mvn/target/BankZbozowyApp]
[INFO] Processing war project
[INFO] Copying webapp resources [/home/runner/work/bank-zbozowy-mvn/bank-zbozowy-mvn/src/main/webapp]
[INFO] Building war: /home/runner/work/bank-zbozowy-mvn/bank-zbozowy-mvn/target/BankZbozowyApp.war
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
```
## Zadanie 6
### 3.
```
[ERROR] Tests run: 6, Failures: 1, Errors: 0, Skipped: 0, Time elapsed: 0.044 s <<< FAILURE! -- in put.io.selenium.atm.AtmCardInfoTest
[ERROR] put.io.selenium.atm.AtmCardInfoTest.testTryPinCorrect -- Time elapsed: 0.008 s <<< FAILURE!
java.lang.AssertionError
	at org.junit.Assert.fail(Assert.java:86)
	at org.junit.Assert.assertTrue(Assert.java:41)
	at org.junit.Assert.assertTrue(Assert.java:52)
	at put.io.selenium.atm.AtmCardInfoTest.testTryPinCorrect(AtmCardInfoTest.java:33)
	at java.base/java.lang.reflect.Method.invoke(Method.java:580)
```
### 5.
Błąd wystąpił przy testach.
Zmiana spowodowała błąd ponieważ błąd jednostkowy testTryPinCorrect spodziewa się starej wartości PIN-u
