# Calculator for BeOS R4, R4.5, and R5.

![](screenshot.png)

This is a very simple scientific calculator meant as an experiment and learning experience in writing for BeOS.  Please send me bugs/questions/gripes, but please don't file lawsuits if your taxes don't come out just right!

## How to install

Since you are reading this document, I'll assume you have already finished installing!  The Calculator is a stand-alone application that can be launched and enjoyed right out of the box.

## How to use:

I will assume you are already familiar with handheld calculators, so I'll omit with the really basic stuff.  Just lanch the application and use it.  However, here are a few subtle points:

The **inv** button is a modifier that gives the _inverse trig functions_.  Click the **inv** button followed by one of the three trig buttons (**sin** **cos** **tan**).  The inverse feature resets itself after each single use.

The **deg** button is a toggle that behaves in the classic unintuitive way:  when the button says _deg_ the trig functions operate in degrees;  clicking the button changes its label to _rad_ and makes trig functions operate in radians.

The **C** button clears the current input.  Clicking **C** a second time in a row resets the calculator's stack and input.

### Keyboard shortcuts:
  * The obvious <kbd>0</kbd> ... <kbd>9</kbd> , <kbd>=</kbd> , <kbd>/</kbd> , <kbd>+</kbd> , <kbd>C</kbd> , <kbd>.</kbd> , etc.
  * <kbd>e</kbd> puts you in exponent mode (i.e. type `16.7e6`).
  * <kbd>p</kbd> gives PI.
  * <kbd>~</kbd> (_tilde_) is the "**-/+**" key used for negating a number.
  * <kbd>Enter</kbd> , <kbd>Return</kbd> both activate the "**=**" key.

You may paste text into the calculator (<kbd>command</kbd>+<kbd>V</kbd>).  This is currently fine for simple expressions, but doesn't allow you to enter stuff that doesn't have a keyboard shortcut (see above).  Sorry.

You may copy from the calculator (<kbd>command</kbd>+<kbd>C</kbd>).  The clipboard is loaded with both text representation and a double-precision floating-point representation.

## Source code

Source code is included in the ZIP file.  You can use the makefile from the command line or use the ".proj" project with Metrowerks IDE.  Since I don't currently have access to a PPC machine, only x86 project building is included.  PPC users can probably use the makefile to build.

___

#### Brought to you by:

Peter Wagner
pwagner@stanfordalumni.org

 

