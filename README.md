# Computational Physics WS 2015/16

The lecture introduces advanced students to numerical methods and concepts relevant for physics. The focus will lie on algorithms for the solution of systems of ordinary differential equations and partial differential equations. Further topics such as root finding and fast Fourier transformation are introduced as needed.

The programming language for this course will be C++. No prior programming experience is required, but knowledge of any programming language is beneficial. Within the lecture all basic concepts of programming in C++ are covered. It is a primary goal of this lecture that each student can write small simulation codes in C++.

The course will consist of 2 hours lecture and 2 hours lab classes. The lab classes will be interactive, i.e. problems have to be solved during the lab class (with help of the assistants). Attendance in the lab classes is mandatory. The lecture will finish with a written exam (Which may be writing a program on the computer, still subject to organizational details).

* __Lecture__ : Wednesdays, 8:30 - 10:30, 5J
* __Lab class 1__: Thursdays, 10:30 - 12:30, 25.22.00.25
* __Lab class 2__: TBA  

# C++

In the course we will use the GNU C++ compiler for Linux. For your homework, you can use any other C++ compiler. This could be for example the *Microsoft Visual C++ compiler* for Windows or *clang* which comes along with the XCode app on Mac OS. However be aware that using compiler specific extensions to C++ is strongly discouraged and may result in a compile failure in the Travis CI setup we are using to compile your homework (which will use GNU C++).

If you want to use the Microsoft Visual C++ IDE, then check out the [Dreakspark](http://www.dreamspark.com/) web-page, where you should be able to get it for free as a student. Not however, that we will not be able to give you any support for this.

# Github

All program codes and lecture notes which will be published throughout the lecture will be made available via the Github website. Even more important,
**all homework program codes will have to be handed in via Github**.  Due to the number of students, we will not accept submissions via email. At the same time becoming familiar with a version control system like *git* is a teaching goal of the lecture.

In order to use Github every student has to create an account there. This is free. You may choose any username you want, we will keep a list which username belongs to whom. The address where you can find all lecture related things is http://github.com/TP1-HHU.

# Linux

The operating system used in the lab classes will be Linux. It is recommended that students make themselves familiar with Linux, since it is the most easy way to get access to a C++ compiler. There is a wide variety of different Linux distributions available. For beginners it might be good to pick one of the more popular distributions, since then you have good chances that you can find a lot of solutions to common problems on the internet. OpenSuse, Fedora and Ubuntu are examples for such distributions.

If you have a Mac, then just grab the XCode package from the app store and subsequently install [MacPorts](https://www.macports.org/). Via MacPorts you can later install all further required software such as GNUplot or CMake.

If you want to run Linux on your computer, you have three different possibilities, each one having advantages and disadvantages:
- install Linux next to your Windows,
- run Linux in a virtual machine under Windows,
- run Linux from a USB drive.

Installing Linux next to Windows and then choose which OS to run at boot time would be the ideal situation. However, if you already have a running Windows on your computer and no free partitions on your hard disk, it is maybe the most complicated out of the three possibilities to set up.

Running Linux in a virtual machine is the preferred option. The basic idea is that you run Linux on a simulated computer under Windows. Sounds slow and complicated, but is rather simple to set-up. The software which you need to simulate that virtual computer is called [VirtualBox](https://www.virtualbox.org) and it is free.

If for some reason the solution using VirtualBox should not work, you can use a USB stick and boot Linux from there. For Windows there is an excellent tool to create a Linux USB stick, the [Linux Live USB creator](http://www.linuxliveusb.com) (short LiLi). It offers a broad range of different Linux distributions which it can download and deploy to the USB stick. Since you will want to make modifications to your live Linux, such as installing additional software (e.g. the C++ compiler) you should choose a distribution which offers *persistence* (see the docs on the LiLi website which Linux distributions offer this feature).

#### Links
- [VirtualBox](https://www.virtualbox.org)
- [Linux Live USB creator](http://www.linuxliveusb.com)
- A [Youtube video](https://www.youtube.com/watch?v=yYMLSpBdRec) on how to use LiLi
- [Microsoft Dreamspark](http://www.dreamspark.com/), the place to go for the Windows C++ compiler
