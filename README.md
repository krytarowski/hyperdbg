# hyperdbg


hyperdbg



A kernel debugger that leverages hardware-assisted virtualization

HyperDbg is a kernel debugger that leverages hardware-assisted virtualization. More precisely, HyperDbg is based on a minimalistic hypervisor that is installed while the system runs. Compared to traditional kernel debuggers (e.g., WinDbg, SoftIce, Rasta R0 Debugger) HyperDbg is completely transparent to the kernel and can be used to debug kernel code without the need of serial (or USB) cables. For example, HyperDbg allows to single step the execution of the kernel, even when the kernel is executing exception and interrupt handlers. Compared to traditional virtual machine based debuggers (e.g., the VMware builtin debugger), HyperDbg does not require the kernel to be run as a guest of a virtual machine, although it is as powerful.

http://hyperdbg.googlecode.com/svn/wiki/images/arch.png

Feel free to contact us for suggestions, criticisms, and bug reports through the HyperDbg google group: http://groups.google.com/group/hyperdbg

Further details about HyperDbg are available in the paper "Dynamic and Transparent Analysis of Commodity Production Systems" (published in the proceedings of ASE 2010). The paper can be downloaded here.







Automatically exported from code.google.com/p/hyperdbg
