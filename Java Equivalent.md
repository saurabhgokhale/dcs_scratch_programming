# Scratch Equivalent of Java Programming

Welcome to Java programming! Let's explore some fundamental concepts that align with the programming blocks you use in Scratch.

## 1. Understanding Movement: "Move" Blocks

In Scratch, you make characters move using the "move" block. In Java, you can use variables and methods to control movement.

![image](https://github.com/saurabhgokhale/dcs_scratch_programming/assets/2688478/d37a42ce-7c22-402a-8d8f-349d9bb82897)

**Equivalent concept in Java:**
```java
// Define a method to move forward a certain number of steps
public void moveForward(int steps) {
    // Logic to move forward
    sprite.setX(sprite.getX() + steps);
}
```

![image](https://github.com/saurabhgokhale/dcs_scratch_programming/assets/2688478/5b435236-adc7-4aa7-8ba3-64852515968b)

```java
// Example: Repeating an action 5 times using a 'for' loop
for (int i = 0; i < 5; i++) {
    // Action to perform (e.g., moving forward)
    moveForward(10);
}
```

![image](https://github.com/saurabhgokhale/dcs_scratch_programming/assets/2688478/cd3c0c2f-487b-473c-95da-e517abd0857d)

```java
// Example: Repeating an action while a condition is true using a 'while' loop
int steps = 0;
while (steps < 50) {
    // Action to perform (e.g., moving forward)
    moveForward(10);
    steps += 10;
}
```

## Additional Info:
- https://lab.scratch.mit.edu/videosprites/
- https://lab.scratch.mit.edu/face/
- https://lab.scratch.mit.edu/text/
