flex

![image](https://github.com/user-attachments/assets/4aaccf03-3610-4c21-a6a8-d003f68d67fd)


The shorthand flexproperty provides a convenient way for specifying how elements stretch and shrink, while simplifying the CSS required. The flexproperty allows you to declare flex-grow, flex-shrink, and flex-basisall in one line.

Note:The flexpropertyis different from the flexvalueused for the displayproperty.

```
.big {
  flex-grow: 2;
  flex-shrink: 1;
  flex-basis: 150px;
}
.small {
  flex-grow: 1;
  flex-shrink: 2;
  flex-basis: 100px;
}
```
In the example above, all elements with class bigwill grow twice as much as elements with class small. Keep in mind, this doesn’t mean bigitems will be twice as big as smallitems, they’ll just take up more of the extra space.

The CSS below declares these three properties in one line.

```
.big {
  flex: 2 1 150px;
}
.small {
  flex: 1 2 100px;
}
```
In the example above, we use the flexproperty to declare the values for flex-grow, flex-shrink, and flex-basis(in that order) all in one line.

```
.big {
 flex: 2 1;
}
```
In the example above, we use the flexproperty to declare flex-growand flex-shrink, but not flex-basis.

```
.small {
  flex: 1 20px;
}
```
In the example above, we use the flexproperty to declare flex-growand flex-basis. Note that there is no way to set only flex-shrinkand flex-basisusing 2 values.

The browser to the right has two flex containers, each with three flex items. In style.css, examine the values for each of these items. Notice that the flex-growand flex-basisvalues are set for the blue divs.

Stretch the browser window to increase its width. Observe that once the top outer divs reach 100 pixels wide, they begin to grow faster than the top center div. Also notice that once the bottom center divreaches 100 pixels wide, it begins to grow faster than the outer divs.

Now, shrink the browser window and notice that once the top center divreaches 50 pixels wide it begins to shrink faster than the outer divs and when the bottom outer divs reach 75 pixels, they begin to shrink faster than the center div.


The shorthand flexproperty provides a convenient way for specifying how elements stretch and shrink, while simplifying the CSS required. The flexproperty allows you to declare flex-grow, flex-shrink, and flex-basisall in one line.

Note:The flexpropertyis different from the flexvalueused for the displayproperty.

```
.big {
  flex-grow: 2;
  flex-shrink: 1;
  flex-basis: 150px;
}
.small {
  flex-grow: 1;
  flex-shrink: 2;
  flex-basis: 100px;
}
```
In the example above, all elements with class bigwill grow twice as much as elements with class small. Keep in mind, this doesn’t mean bigitems will be twice as big as smallitems, they’ll just take up more of the extra space.

The CSS below declares these three properties in one line.

```
.big {
  flex: 2 1 150px;
}
.small {
  flex: 1 2 100px;
}
```
In the example above, we use the flexproperty to declare the values for flex-grow, flex-shrink, and flex-basis(in that order) all in one line.

```
.big {
 flex: 2 1;
}
```
In the example above, we use the flexproperty to declare flex-growand flex-shrink, but not flex-basis.

```
.small {
  flex: 1 20px;
}
```
In the example above, we use the flexproperty to declare flex-growand flex-basis. Note that there is no way to set only flex-shrinkand flex-basisusing 2 values.

The browser to the right has two flex containers, each with three flex items. In style.css, examine the values for each of these items. Notice that the flex-growand flex-basisvalues are set for the blue divs.

Stretch the browser window to increase its width. Observe that once the top outer divs reach 100 pixels wide, they begin to grow faster than the top center div. Also notice that once the bottom center divreaches 100 pixels wide, it begins to grow faster than the outer divs.

Now, shrink the browser window and notice that once the top center divreaches 50 pixels wide it begins to shrink faster than the outer divs and when the bottom outer divs reach 75 pixels, they begin to shrink faster than the center div.
