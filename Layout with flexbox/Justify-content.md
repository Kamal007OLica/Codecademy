justify-content

8 min

In previous exercises, when we changed the displayvalue of parent containers to flexor inline-flex, all of the child elements (flex items) moved toward the upper left corner of the parent container. This is the default behavior of flex containers and their children. We can specify how flex items spread out from left to right, along the main axis. We will learn more about axes in a later exercise.

To position the items from left to right, we use a property called justify-content.

```
.container {
  display: flex;
  justify-content: flex-end;
}
```
In the example above, we set the value of justify-contentto flex-end. This will cause all of the flex items to shift to the right side of the flex container.

Below are five commonly used values for the justify-contentproperty:

- flex-start— all items will be positioned in order, starting from the left of the parent container, with no extra space between or before them.
- flex-end— all items will be positioned in order, with the last item starting on the right side of the parent container, with no extra space between or after them.
- center— all items will be positioned in order, in the center of the parent container with no extra space before, between, or after them.
- space-around— items will be positioned with equal space before and after each item, resulting in double the space between elements.
- space-between— items will be positioned with equal space between them, but no extra space before the first or after the last elements.
In the definitions above, “no extra space” means that margins and borders will be respected, but no more space (than is specified in the style rule for the particular element) will be added between elements. The size of each individual flex item is not changed by this property.
![image](https://github.com/user-attachments/assets/bef15e8d-2135-4ae1-8271-93795f1591e1)

```


#flexstart {
  display: flex;
  justify-content: flex-start;
}

#flexend {
display: flex;
  justify-content: flex-end;
}

#center {
  display: flex;
  justify-content: center;
}

#spacearound {
  display: flex;
  justify-content: space-around;
}

#spacebetween {
  display: flex;
  justify-content: space-between;
}
```



---





Flex Start


