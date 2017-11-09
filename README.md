# Computer Methods for Science

Kurtsu hau zientzian konputazioa erabiltzen edota ikasi nahi dutenentzat zuzendua dago.
Bertan programazioaren arlo garrantzitsuenak eta kodean oinarritutako edonolako lanen bertsioen kudeaketa ikasiko dugu.
Kurtsoan zehar emandako informazio dena ingelesez topa daitekeenez Interneten, eta kodean oinarritutako elkarlan gehienetan erabiltzen den hizkuntza ingelesa denez, hemendik aurrera ingelesa erabiliko dugu.

Este curso está dirigido a quienes quieran aprender las bases de los metodos más usados en la computacion para la ciencia.
Se cubrirán los aspectos más importantes de la programación y además se aprendera a controlar las versiones de cualquier trabajo que esté basado en código de programación.
Como la información facilitada durante el curso se puede encontrar en su integridad en inglés en Internet, y como para la mayor parte de trabajos colavorativos el idioma vehicular es en mayor parte el ingles, usaremos este idoma a partir de ahora.

## Main tools

In this curse we will study the basics of scientific programming and how to organize and control the work we do in our code and share it with other people for collaborating.
For this we will use two different main tools Git and Julia.

### Git

First of all, we need to install git into our computers.
We will use git as a version control software as well as to download the necessary material of this course.
This way one becomes familiar with this great tool used in lots of projects from the beginning.

To install git into your computers you must follow the steps for your own operative system (OS), which appear well documented in [https://git-scm.com/download/](https://git-scm.com/download/).
In this website one can also find all the necessary information about its usage.
So if you are more interested in this tool you can read the documentation as a good exercise to improve your skill on the version control world.

Once installed git into your computer, you should be able to do things like `$ git init` on Unix-like systems (Linux and Mac OS) or `C\> git init` on Windows, to start a new project controlled by versions and comments usually referred as repository.
As you see the command is essentially equal in both cases, so we will skip the differentiation between OSs until necessary for clarification.

### Julia

Julia is a high-level high-performance multipurpose programming language.

What do we mean by high-level?
The Julia language is closer connected with the human like instructions than with the machine 0s or 1s or the Assembly code.
It comes with lots of preloaded functions and libraries which make matrix multiplications, parallel computing, mathematical functions, I/O, networking, and so on, as easy as possible.

What do we mean by high-performance?
Usually to achieve high performance we need to use low-level languages like C/C++ or FORTRAN, even ASSEMBLY.
In this case performances comparable with the obtained by the mentioned languages are achieve thanks to the Julia compiler.

Finally, the language is multipurpose, mostly like Python and so on, because any task one wants to implement with Julia into the computer can be written in Julia, which is not the case for languages like MATLAB and other scientific programming languages.

To install Julia into your computer follow the necessary steps for your OS found in [https://julialang.org/downloads/](https://julialang.org/downloads/).

## Program

The course is divided into two main categories.
This doesn't mean that they will be divided also chronologically, not at all.
The version control will be introduced and mastered while some programming skills are acquired, to the point that we will be able to work collaboratively with other people even remotely using git.

### 0 - Download the course and preliminary things

Lear the basics to use the terminal. For instance, move yourself to different paths, create new folders, new files, delete, move and copy, and so on.
Create a work-space for the course. Install the requisites and download the curse.

### A - Version control systems (with Git)

The first points are to create a project and initialize the repository.
Then we will learn how to commit the changes, create branches, and merge them.
Finally, we will create a remote to connect it with our local repository and to collaborate with your team.
For this regard, we will learn how to use GitLab as remote and issue tracker.
We will also familiarize with GitHub too.

### B - Programming (with Julia)

Introduction to programming languages. Interacting with Julia trough the REPL. Define variables, which are the number types and elementary functions.
Introduce to the control flow with `if`, `for`, `while` and so on.
Introduction to Jupyter, an interactive multi-language scientific programming environment.
Introduction to multi-dimensional arrays and linear-algebra. Introduction to functions, types and modules. Introduction to parallel computing. Introduction to meta-programming.
