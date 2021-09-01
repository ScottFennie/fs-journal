# JS Proxy Objects!

## What are the two common operations that we will set in the handler?

The get and set operations will always be set in the handler.

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?

the get function will often times not return the value stored in the key. To fix this we need to ensure that we are creating a custom override called a trap and applying it to the get.

## What are some of the benefits of the proxy object that we are using in our structure for applications?

The main benefit we receive from the proxy object structure is security. This will be incredibly beneficial as our applications get larger and larger.


9/1 Project Link: https://scottfennie.github.io/fall21-gregslist/