## Task lists

```no-highlight
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

Result:

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

## Emphasis

```no-highlight
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

## Headers

```no-highlight
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Lists

```no-highlight
1. First ordered list item
1. Another item
1. And another item. 
```

1. First ordered list item
1. Another item
1. And another item.

## Images

```no-highlight
![](https://picsum.photos/400)
```

![](https://picsum.photos/400)


## Code

    ```python
    s = "Python syntax highlighting"
    print s
    ```

```python
s = "Python syntax highlighting"
print s
```

## Markdown tables

Bootstrap stylizes tables based on the `table` class which requires a shortcode. (optionally) The shortcode can accept `class` [arguments](https://getbootstrap.com/docs/4.1/getting-started/introduction/) (`table-stripe` and `table-bordered` demonstrated below).

```no-highlight
{{</* table `table-striped table-bordered` */>}}
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
{{</* /table */>}}
```
Result:

{{< table `table-striped table-bordered` >}}
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
{{< /table >}}