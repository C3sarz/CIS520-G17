----------------------------------------------------------------
# Project 1
## CIS 520 - Operating Systems 1 -  Group 17
----------------------------------------------------------------
[Notes and modified files](https://github.com/C3sarz/CIS520-G17/blob/master/notes.txt)

TODO List:
1. Timer_sleep():

	Tests:
   - pass tests/threads/alarm-single
   - pass tests/threads/alarm-multiple
   - pass tests/threads/alarm-simultaneous   
   - pass tests/threads/alarm-zero
   - pass tests/threads/alarm-negative

2. Priority Scheluder

- Priority donation srews up ready queue order.
- list_ordered orders the ready_list for set_thread_priority 

	Tests:
	- pass tests/threads/alarm-priority
	- pass tests/threads/priority-change
	- FAIL tests/threads/priority-donate-one		~order is correct but fails due to whitespace (???)
	- FAIL tests/threads/priority-donate-multiple
	- FAIL tests/threads/priority-donate-multiple2
	- FAIL tests/threads/priority-donate-nest
	- FAIL tests/threads/priority-donate-sema
	- FAIL tests/threads/priority-donate-lower
	- pass tests/threads/priority-fifo
	- pass tests/threads/priority-preempt
	- FAIL tests/threads/priority-sema
	- FAIL tests/threads/priority-condvar
	- FAIL tests/threads/priority-donate-chain

3.  Advanced Scheduler
