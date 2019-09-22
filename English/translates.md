# Program Execution

An operating system’s most basic function is to support the running of programs by the users. On a multiprogramming operating system, running programs are commonly referred to as processes. Process management refers to the facilities provided by the operating system to support the creation, execution, and destruction of processes, and to facilitate various interactions, and limit others. The operating system’s kernel in conjunction with underlying hardware must support this functionality. Executing a program involves the creation of a process by the operating system. The kernel creates a process by setting aside or allocating some memory, loading program code from a disk or another part of memory into the newly allocated space, and starting it running.

> Большинство операционных систем поддерживает запуск пользовательских программ. Запуск программ на мультипрограммируемой операционной системе обычно называют процессами. Управление процессами относится к предустановленным средствам операционной системы поддерживающей создание, выполнение и уничтожение процессов и для облегчения различных взаимодействий. Ядро операционных систем вместе с базовым железом должны поддерживать эту функцию. Исполнение программ включает в себя создание процесса в операционной системе. Ядро создаёт процессы откладывания в сторону или выделения памяти, загружает программный код с диска или другой области памяти в ново выделенное пространство и начинает запуск.  

Operating system kernels store various information about running processes. This information might include: A unique identifier, called a process identifier (PID); A list of memory the program is using, or is allowed to access; The PID of the program which requested its execution, or the parent process ID (PPID); The filename and/or path from which the program was loaded; A register file, containing the last values of all CPU registers; A program counter,indicating the position in the program.

> Ядра операционной системы хранят вариативную информацию о запущенных процессах. Эта информация может содержать: уникальный ID, индентификатор процесса; список программ используемых программ или разрешённых доступов; идентификатор процесса который запросил исполнения или идентификатор родительского процесса; название файла и/или путь откуда программа была загружена; реестр файла, содержащий последние значения всех регистров ЦП; программный счётчик, сообщающий позицию программы.

---

# Graphical User Interfaces

Most modern computer systems support graphical user interfaces (GUI), and often include them. In some computer systems, such as the original implementations of Microsoft Windows and the Mac OS, the GUI is integrated into the kernel.

> Множество современных компьютерных систем поддерживают графический интерфейс пользователя (ГУЙ), и зачастую они включены. В некоторых компьютерных системах, таких как оригинально реализованных MS Windows и Mac OS, ГУЙ интегрирован в ядро.

While technically a graphical user interface is not an operating system service, incorporating support for one into the operating system kernel can allow the GUI to be more responsive by reducing the number of context switches required for the GUI to perform its output functions. Other operating systems are modular, separating the graphics subsystem from the kernel and the Operating System. In the 1980s UNIX, VMS and many others had operating systems that were built this way. Linux and Mac OS X are also built this way. Modern releases of Microsoft Windows such as Windows Vista implement a graphics subsystem that is mostly in user-space, however versions between Windows NT 4.0 and Windows Server 2003’s graphics drawing routines exist mostly in kernel space. Windows 9x had very little distinction between the interface and the kernel.

> Хотя технически графический интерфейс пользователя не является службой операционной системы

Many computer operating systems allow the user to install or create any user interface they desire. The X Window System in conjunction with GNOME or KDE is a commonly-found setup on most Unix and Unix-like (BSD, Linux, Minix) systems. A number of Windows shell replacements have been released for Microsoft Windows, which offer alternatives to the included Windows shell, but the shell itself cannot be separated from Windows.

> Translate

Numerous Unix-based GUIs have existed over time, most derived from XI1. Competition among the various vendors of Unix (HP, IBM, Sun) led to much fragmentation, though an effort to standardize in the 1990s to COSE and CDE failed for the most part due to various reasons, eventually eclipsed by the widespread adoption of GNOME and KDE. Prior to open source-based toolkits and desktop environments, Motif was the prevalent toolkit/desktop combination (and was the basis upon which CDE was developed).

> Translate

Graphical user interfaces evolve over time. For example, Windows has modified its user interface, almost every time a new major version of Windows is released, and the Mac OS GUI changed dramatically with the introduction of Mac OS X in 2001.

> Translate
