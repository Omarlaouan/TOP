# Flexbox
Flexbox is a way to arrange items in rows or columns 
"Flex" = growing or shrinking

### Flex container and flex items
- Flex container = contains flex items, have property display: flex
- Flex items = Are inside a container
- A flex item can be a flex container by adding property display: flex, and can contain flex items itself
- With flexbox, you can create and nest flex containers and items as you want

Questions : 
- didnt understand the two examples (why flex items are created differently? )


### Growing an shrinking
flex shorthand : let you set the values of multiples properties at once. 

flex = flex-grow; flex-shrink, flex-basis

examples : 

div {
    flex: 1;
}

is equivalent to : 

div {
    flex: 1 1 0;
}

is equivalent to : 

div {
    flex-grow: 1;
    flex-shrink: 1;
    flex-basis: 0;
}

NB : if flex-grow and flex-shrink are specified, the width value is not respected. 
It depends on the size of parents : 
- if parent bigger, they will grow to fill in,
- if parent smaller, they will shrink to fill in. 


Mdn lesson on flexbox : 
