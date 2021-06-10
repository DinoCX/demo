# demo
rdtsc
xor ecx,ecx
add ecx, eax
rdtsc
sub eax, ecx
cmp eax, 0xFFF
jb popup
rdtsc
push eax
mov    eax,0x4094e4
call   eax
popup:
