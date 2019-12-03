# DA-ex2

Implement Suzuki’s and Kasami’s algorithm for mutual exclusion in a distributed system with Java/RMI.

## TODO
- Main.java
    - Create the components *Done*
    - Create threads of the components *Done*
    - It must be possible to specify the number of components
- Component.java
    - The functionality of registering and looking up components
    - The global framework of the Component class *Done? I guess not completely*
    - Implement broadcasting, receiving a request
    - Include random delays in the CS and btw the finishing execution of CS and a new access request.
    - Implement token send and receive
- [Token Implementation][1]
- Program
    - The output of the algorithm should it possible to check its correct operation. (wtf?)

## Problems

- try/catch statment for main(String[] args)
- Component.java:57: error: exception MalformedURLException is never thrown in body of corresponding try statement
            } catch (MalformedURLException | RemoteException | NotBoundException e) {
    - it means these exceptions will never happen, is it because the code is not complete yet or something else?                

## TOKEN
[1]:
- The token is a true/false object
- It has a queue and an array

**question** 

*should it be a class?*

*It is ONLY one object*

## Material
- https://www.youtube.com/watch?v=aWne_qIR2XI
- BrightSpace/Course Information/Course Description.pdf pg. 66
- BrightSpace/Lectures/Chapter4/01-IN4150-mutual-exclusion-2019-2020.ppt




