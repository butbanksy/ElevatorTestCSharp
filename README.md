# SQLi Elevator Test in C# [WIP]

[![N|Solid](https://sqli.developpez.com/logo-sqli.png)](https://sqli.com/)

This is SQLi's Elevator Test in C#. It was originally made for the Java Language.

### Description
This test is about a building having several elevators with different states.
For example, each elevator can be at a different level, and can be going up, or down.

The objective of this exercise is to write a program that will identify elevator will be served once a request for an elevator is registered.

Please note these rules :
- An elevator is requested by default from top floor.
- An elevator can be resting at a given floor, going up or going down.
- An elevator switch automatically his direction when reaching the edges of the building (means the first and top floors). 
- An elevator can not switch his direction in the middle of a building.
    Example: in a building of 10 floors, an elevator at the 3rd floor and
    ascending can never go down before reaching the 10th floor. And vice
    versa.

- An elevator is never in between floors.





### Todos

 - Add the test's description as a comment in the test file.
 - Add more test cases to make it more challenging.

