# C# Data Types

## What are the three categories of data types? How are they different?

1) Value Type
-Holds the data within its own memory space.
2) Reference Type
-Contains a reference that points to another location where the data is stored.
3) Pointer Type
-Holds the memory address of another type

## What are the Value-type data types? What differences do you notice from JavaScript?

The value types are as follows:
1) bool
2) byte
3) char
4) decimal
5) double
6) enum
7) float
8) int
9) long
10) sbyte
11) short
12) struct
13) uint
14) ulong
15) ushort


As you can see from the extensive list above, C# has many more value data types than Javascript, allowing you to be incredibly specific with the type.

## In your own words how do Reference types get stored in memory? How does this differ from Value types?

Reference types store essentially a key that points to a location where a full data set is stored rather than simply storing all of the data itself. This allows for the same variable to utilized multiple places without moving a lot of data around.

Project: https://github.com/ScottFennie/RPS