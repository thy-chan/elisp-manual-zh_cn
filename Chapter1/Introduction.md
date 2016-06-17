# Introduction
前言

Most of the GNU Emacs text editor is written in the programming language called Emacs Lisp.
You can write new code in Emacs Lisp and install it as an extension to the editor. 
However, Emacs Lisp is more than a mere “extension language”; it is a full computer programming language in its own right. 
You can use it as you would any other programming language.

大多数情况下GNU Emacs 文本编辑器是在 Emacs Lisp 编程语言上编写的。
你可以编写和安装新的代码用于扩展Emacs 编辑器。
然而， Emacs Lisp 不仅仅是一种扩展语言，它自己本身就具有完整的计算机编程语言能力。
你可以使用它就像你使用任何其他编程语言一样。

Because Emacs Lisp is designed for use in an editor, it has special features for scanning and parsing text as well as features for handling files, buffers, displays, subprocesses, and so on. Emacs Lisp is closely integrated with the editing facilities; thus, editing commands are functions that can also conveniently be called from Lisp programs, and parameters for customization are ordinary Lisp variables.

因为Emacs Lisp 被设计给编辑器使用， 它具有特殊功能用于扫描和解析以及处理文件、缓冲区、显示、子进程等等。
Emacs Lisp 与编辑功能的紧密结合；因此，编辑命令功能也可以很方便的被Lisp 程序调用，以及为普通Lisp 变量定制参数。

This manual attempts to be a full description of Emacs Lisp. For a beginner’s introduction to Emacs Lisp, see An Introduction to Emacs Lisp Programming, by Bob Chassell, also published by the Free Software Foundation. This manual presumes considerable familiarity with the use of Emacs for editing; see The GNU Emacs Manual for this basic information.

这本手册试图去完整描述Emacs Lisp。给初学者介绍Emacs Lisp 出示的Emacs Lisp编程是由Bob Chassell，同时也是由自由软件基金会发布的。本手册假定可以与Emacs 熟练操作编辑；查看 GNU Emacs 手册给出的基本信息。

Generally speaking, the earlier chapters describe features of Emacs Lisp that have counterparts in many programming languages, and later chapters describe features that are peculiar to Emacs Lisp or relate specifically to editing.

一般来说，前面章节描述了Emacs Lisp 与许多编程语言具有的一些相似功能，后面章节介绍Emacs Lisp具有的特性或有关特殊编辑功能。

This is the GNU Emacs Lisp Reference Manual, corresponding to Emacs version 24.5.

这是GNU Emacs 参考手册，对应Emacs 24.5 版本。


## 注意事项 （Caveats）

This manual has gone through numerous drafts. It is nearly complete but not flawless. There are a few topics that are not covered, either because we consider them secondary (such as most of the individual modes) or because they are yet to be written. Because we are not able to deal with them completely, we have left out several parts intentionally.

手册经过很多草案， 它几乎是完整的，但并非是无懈可击的。也有一些主题没有去涉及，或者因为我们认为他们是次要的（例如大多个人模式），或因为他们还没有来得及写入。我们留下了部分因为我们不能完全顾及到他们
