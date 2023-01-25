# Language

_What is the name of the language? Link the name to its webpage
(if appropriate)._

G language
https://www.ni.com/en-us/shop/labview.html

# Domain

_Describe the language's domain in five words._

 Instrument Control with Sensor Input.

# Computational model

_We don't yet have a great definition of the term "computational model".
For now, try to come up with the clearest, most concise explanation of
what happens when a program in your DSL runs._

The language allows you to program the speeds/duration of things like motors and other hardware equipment. It also allows the user to take in inputs from the outside world using sensors, and use these measurements in real time to influence how a particular robot or machine moves. So when you load the program onto a bot and run it, the bot will do things as you program it, while also being able to respond to external stimuli in real time. That makes this language particularly useful for automation. 

# DSL-ness

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_

It actually lies somewhere in the middle now. While it largely specializes in automation and sensory data collection - it does have loops and variables and if statements - allowing you to do other kinds of programming. It is not the ideal language to use for general programming though. In an interview with the creator of the language, he states that while the language was original designed specifically for scientists to help them operate "measuring systems" - it is now used for a wider field of activity. 

# Internal or external?

_Is the language implemented as an internal or external DSL?
Justify your answer._

G is an External DSL. Code written in G is not valid in C/C++. It just does its own thing. It is not an embedded DSL.


# Host language

_What language(s) was (were) used to implement the DSL?_

C, C++

# Benefits

_Identify one potential benefit of the DSL: how is a programmer's life made
easier by the existence of this language?_

Firstly, G uses a Graphical User Interface. There are blocks which can be dropped onto the palete and these blocks then control a robot(or really any machine). This makes it very easy to program a robot -  to make it move, turn on LED lights, make sounds, etc. There is no big learning curve, and it can be useful to quickly give a set of commands to a machine.

You do not need to know any programming language to be able to use this.

There are a lot of shortcuts designed for data collection and automation. You do not need to know the internal workings of a particular system to write a program for it using G.

# Drawbacks

_Identify one potential drawback of the DSL: what does a programmer
lose by using this DSL instead of a general-purpose language?_

- Larger, more complex codes can get really clunky and it lacks flexibility outside of programming motors and LEDs to do things. Recursion and other algorithms require a lot more steps and take up a lot of screen space. 

- Since it uses a graphical user interface, older and slower computers have a tough time running the software. 
