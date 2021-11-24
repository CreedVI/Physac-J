# Physac-J
A handmade version of Physac for Java

<hr>

## About
Physac-J is a Java recreation of the Physac physics library written by Victor Fisac 
([@victorfisac](https://github.com/victorfisac)) and Ramon Santamaria([@raysan5](https://github.com/raysan5))
for use in [Raylib-J](https://github.com/CreedVI/Raylib-J).

<hr>

## Usage
### Raylib-J:
In version 0.4 or higher of Raylib-J Physac-J is available via the `physac` module of the raylib instance.
```java
Raylib rlj = new Raylib(800, 600, "Example Code");
rlj.physac.InitPhysics();
        ...
```

### Standalone:
First, include the release .jar in your project. Then create a new `Physac` object. 
```java
Physac physics = new Physac();
physics.InitPhysics();
        ...
```

<hr>

## Thanks
Thanks to Victor Fisac ([@victorfisac](https://github.com/victorfisac)) and Ramon Santamaria([@raysan5](https://github.com/raysan5))
for creating the original library and releasing it so people like me can do projects like this!
