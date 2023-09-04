# PaliaTools6-GlsRunning-1-
Pure virtual function (GlsRunning ==1)

The error message "Pure virtual function being called while application was running (GlsRunning 1)" typically occurs in C++ or similar programming languages when an application attempts to call a pure virtual function while it's running. Here's what this generally means:

Pure Virtual Function: A pure virtual function is a function declared in a base class but without any implementation in that base class. It is marked as "pure virtual" using the "= 0" syntax at the end of its declaration. Derived classes are required to provide an implementation for this function.

Calling the Pure Virtual Function: The error you're seeing occurs when the program attempts to call this pure virtual function from an instance of the base class. This is incorrect because there is no implementation of the function in the base class.

Jxmmy -

Please try to download the latest Microsoft visual C++ Here and see if it helps https://aka.ms/vs/17/release/vc_redist.x64.exe

![image](https://github.com/Popolia/PaliaTools6-GlsRunning-1-/assets/69745473/f0921ee1-5622-40a4-9566-8237ded9201a)
