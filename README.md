# Gamma UI

A clean, simple, and responsive CSS framework

- [Grid](#grid)
- [Font](#font)
- [Spacing](#spacing)
- [Color](#color)
- [Buttons](#buttons)

## Grid

---

Works on a 12 column grid using with each number representing how many grid columns the element will take up

The classes are named using the format col-{numOfCols}

- `col-1` will span 1 column at 100% width

- `col-6` will span half the container or equal to 6 columns

- and so on until `col-12`

Must be inside a container

```
<div class="container">
    <div class="col-12">
    </div>
</div>
```

## Font

---

The classes are named using the format fw-{weight}

- light - 300

- regular - 400

- medium - 500

- bold - 700

- black - 900

## Spacing

---

The classes are named using the format {property}{sides}-{size}

### Property

- m - for classes that set margin

- p - for classes that set padding

### Sides

- t - for classes that set margin-top or padding-top

- b - for classes that set margin-bottom or padding-bottom

- s - (start) for classes that set margin-left or padding-left in LTR, margin-right or padding-right in RTL

- e - (end) for classes that set margin-right or padding-right in LTR, margin-left or padding-left in RTL

- x - for classes that set both left and right

- y - for classes that set both top and bottom

- blank - for classes that set a margin or padding on all 4 sides of the element

### Size

- 0 - for classes that eliminate the margin or padding by setting it to 0

- 1 - (by default) for classes that set the margin or padding to $spacer * .25

- 2 - (by default) for classes that set the margin or padding to $spacer * .5

- 3 - (by default) for classes that set the margin or padding to $spacer

- 4 - (by default) for classes that set the margin or padding to $spacer * 1.5

- 5 - (by default) for classes that set the margin or padding to $spacer * 3

- m-auto - for classes that set the margin to auto

## Color

---

Colors are defined in the `:root` class at the beginning of the css file

## Buttons

---

Button format is created with `btn`

The color and style classes are named using the format btn-{outline}-{color}

outline variable is optional and will be a border only button

A button class would look like `btn btn-primary`
