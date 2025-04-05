# SOUTHERN_CROSS_SYSTEM_CALLS
A list of the Southern Cross Monitor System Calls

This is the general form of programs to use the subroutine in the Monitor.

; set up registers
	LD A,nn
	LD HL,nnnn
	
; system call
	LD C,call number or call name
	RST 30H
	
	INCLUDE		"SCM18_Include.asm" ; if using LD C,call name

I created this list to help me use Monitor calls, I hope it helps other users.
