# Structs
---

Structures hold related data together that we want to perform operations on.

To define a struct we can do the following:
```cpp
Player :: struct {

}
```

Let's add an x and y to our player struct. We do this by specifying the variable name and type inside the struct body.
```cpp
Player :: struct {
    x: int,
    y: int,
}
```

```shell
Note: Default values are not allowed inside structs.
```

Inside main, we can now create an instance of Player.
```cpp
player: Player
// Set player values.
player.x = 25
player.y = -50
```

We can also set the values of the members upon initialization. We do this by creating a block that contains named members equal to some value.
```cpp
player: Player = {
    x = 25,
    y = -50,
}
```

In Chapter 3 we will look at how we can create procedures to perform operations on our data.
