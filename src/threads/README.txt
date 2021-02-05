///////////////////////////////
Project 0 - CIS 520
By: Cesar Zavala
///////////////////////////////

Summary:

To implement the "alarm-mega" test (creates 5 threads that sleep 70 times), we must modify a few files in the pintos/src/tests/threads directory. The following files were modified:

+Rubric.alarm:
	-Added "alarm-mega"	
	
+tests.c
	-Added {"alarm-mega", test_alarm_mega}
	
+tests.h
	-Added "extern test_func test_alarm_mega;"
	
+Make.tests
	-Added alarm-mega to the test names.
	
+alarm-wait.c
	-Added the "test_alarm_mega" function.
	
