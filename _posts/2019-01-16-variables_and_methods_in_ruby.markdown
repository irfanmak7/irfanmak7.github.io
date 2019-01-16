---
layout: post
title:      "Variables and Methods in Ruby"
date:       2019-01-16 14:30:32 -0500
permalink:  variables_and_methods_in_ruby
---


### Ruby Variables


**Local Variables:** Variables defined in a method. Local variables are not available outside the method. Local variables begin with a lowercase letter or _.

**Instance Variables:** Variables available across methods for any particular instance or object. That means that instance variables change from object to object. Instance variables are preceded by the at sign @ followed by the variable name.

**Class Variables:** Variables available across different objects. A class variable belongs to the class and is a characteristic of a class. They are preceded by the sign @@ and are followed by the variable name.

**Global Variables:** Class variables are not available across classes. If you want to have a single variable, which is available across classes, you need to define a global variable. The global variables are always preceded by the dollar sign $.

### Ruby Methods

Ruby methods are very similar to functions in any other programming language. Ruby methods are used to bundle one or more repeatable statements into a single unit.

Method names should begin with a lowercase letter. If you begin a method name with an uppercase letter, Ruby might think that it is a constant and hence can parse the call incorrectly.

Methods should be defined before calling them, otherwise Ruby will raise an exception for undefined method invoking.

Methods can also accept parameters, but you will have to remember the number or parameters when you call a method.

You can set default values for the parameters, which will be used if method is called without passing the required parameters.

Every method in Ruby returns a value by default. This returned value will be the value of the last statement.

The return statement in ruby is used to return one or more values from a Ruby Method. If more than two expressions are given, the array containing these values will be the return value. If no expression given, nil will be the return value.
