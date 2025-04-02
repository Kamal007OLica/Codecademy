align-items

8 min

In the previous exercise, you learned how to justify the content of a flex container from left to right across the page. It is also possible to align flex items vertically within the container. The align-itemsproperty makes it possible to space flex items vertically.

```
.container {
  align-items: baseline;
}
```

In the example above, the align-itemsproperty is set to baseline. This means that the baseline of the content of each item will be aligned.

Below are five commonly used values for the align-itemsproperty:

- flex-start— all elements will be positioned at the top of the parent container.
- flex-end— all elements will be positioned at the bottom of the parent container.
- center— the center of all elements will be positioned halfway between the top and bottom of the parent container.
- baseline— the bottom of the content of all items will be aligned with each other.
- stretch— if possible, the items will stretch from top to bottom of the container (this is the default value; elements with a specified height will not stretch; elements with a minimum height or no height specified will stretch).
These five values tell the elements how to behave along the cross axisof the parent container. In these examples, the cross axis stretches from top to bottom of the container. We’ll learn more about this in a future exercise.

You might be unfamiliar with the min-heightand max-heightproperties, but you have used heightand widthbefore. min-height, max-height, min-width, and max-widthare properties that ensure an element is at least a certain size or at most a certain size. You’ll see how these become useful as you move throughout this lesson.
![image](https://github.com/user-attachments/assets/f7f4e95a-e083-4947-9e53-3ef9958edc4a)

Now you’re going to see each of the five values above in action!
