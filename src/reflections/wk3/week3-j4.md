# The All-Seeing Observer

## What problems does the Observer Pattern seek to solve?

This pattern makes it so you don't need to continuously envoke a draw function every time you alter the appstate manually.

## What are the three mechanisms of the observer pattern?

1) Subscribe

2) Unsubscribe

3) Broadcast

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.


As a function updates the array within the appState, the listener pics that up and calls upon the draw function ensuring that the user is always seeing the most up-to-date information.


Daily Project: https://scottfennie.github.io/SportingGoods/