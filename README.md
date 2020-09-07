# turtle-python
turtle is a pre-installed Python library that enables users to create pictures and shapes by providing them with a virtual canvas. The onscreen pen that you use for drawing is called the turtle and this is what gives the library its name.


The object-oriented interface uses essentially two+two classes:

1. The TurtleScreen class defines graphics windows as a playground for the drawing turtles. Its constructor needs a tkinter.Canvas or a ScrolledCanvas as argument. It should be      used when turtle is used as part of some application.
   The function Screen() returns a singleton object of a TurtleScreen subclass. This function should be used when turtle is used as a standalone tool for doing graphics. As a        singleton object, inheriting from its class is not possible.

    All methods of TurtleScreen/Screen also exist as functions, i.e. as part of the procedure-oriented interface.
    
    
2. RawTurtle  defines Turtle objects which draw on a TurtleScreen. Its constructor needs a Canvas, ScrolledCanvas or TurtleScreen as argument, so the RawTurtle objects know where    to draw.

    Derived from RawTurtle is the subclass Turtle (alias: Pen), which draws on “the” Screen instance which is automatically created, if not already present.

    All methods of RawTurtle/Turtle also exist as functions, i.e. part of the procedure-oriented interface.
