Alleria is a profiling framework that can generate instruction and memory access traces for a whole application or specific parts of an application. The generated traces can be used for off-line analysis. It's based on the Intel Pin dynamic binary instrumentation framework. The Alleria framework consists of two components: a profiling tool and a library for reading from generated profiles. Two types of profiles can be generated: binary and textual. The binary profiles are much smaller in size, and therefore can be generated much more efficiently. However, the Alleria library has to be used to analyze the traces. Textual profiles add a significant profiling overhead, but the generated profiles can be inspected using a text editor. 

Alleria can capture many pieces of information, including: virtual addresses, physical addresses, accessed values and their sizes, virtual addresses of executed (and retired) instructions, binary encodings of the executed instruction, OS thread identifiers of the context in which the instructions got executed, OS process identifiers, executable binary paths that contain the instructions, names of executed functions (requires debugging information), timestamps associated with executed instructions, and many other pieces of information for advanced use cases including information related to system calls, function calls, thread scheduling, memory management, and others.

The name "Alleria" was inspired by a character called [Alleria](https://wow.gamepedia.com/Alleria_%28Warcraft_II%29) from the Warcraft II video game.

## Compiling Alleria on Windows
Alleria should work on Windows 8 and later. However, the currently available build files only work on Windows 10. But with minor changes, it's possible to build Alleria on earlier versions of Windows. 

The compilation instructions will be published soon.

## Running Alleria on Windows
These instructions will be published soon.

## Compiling and Running Alleria on Linux
Most of Alleria's source code can be compiled on Linux. But we've not written the build files for Linux. In addition, the implementation of the Linux-specific functions in PortableApi.cpp needs to be completed and these functions need to be tested. This is a work in progress.
