# magic 8 challenges

Coding challenges for the magic 8 tutorial

## Before we get started

Complete the following [guided tutorial](/lessons/magic-8/activity), and your code should look like this:

```blocks
basic.showString("ASK A QUESTION")
basic.showNumber(8)
input.onGesture(Gesture.Shake, () =>  {
    basic.clearScreen()
    let randomNumber = randint(0, 2)
    if (randomNumber == 2) {
        basic.showString("YES")
    } else if (randomNumber == 1) {
        basic.showString("NO")
    } else {
        basic.showString("I DON'T KNOW")

    }
    basic.showNumber(8)

})
```
