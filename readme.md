(gdb) info functions
	0x08048b20  phase_1
	0x08048b48  phase_2
	0x08048b98  phase_3
	0x08048ca0  func4
	0x08048ce0  phase_4
	0x08048d2c  phase_5

Set up break point:
    (gdb) b phase_1
    Breakpoint 1 at 0x8048b26
    (gdb) r
    Starting program: /root/Downloads/sheldon1
    Welcome to my fiendish little bomb. You have 6 phases with
which to blow yourself up. Have a nice day!

