# C# Inheritance

## What does Inheritance accomplish for us in C#?

Inheritance in C# gives the developer the power to define a relationship between two classes, defining one as the derived class, and one as the base class. This gives us the opportunity to extend classes rather than create new ones.

## How does Member inheritance work in C#? Does a class inherit all members of the base class?

In C# derived classed inheret eveything except for the constructoor and the finalizers from the parent(base) class.

## How does accessibility affect inheritance?

In order for a member to be properly inherited from a parent class, it must be "visible" to that class. Fro example, if a member is marked as private on the parent class, it wont be accesible to the child class.

Project link: (Today I got help with an aspect of my capstone project) https://github.com/ScottFennie/Sprintr