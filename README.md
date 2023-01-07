<p align="center">
<img  width="100px" src="./images/Logo.png"></img>
</p>

<h1 style="text-align:center">Gamma UI</h1>

![GitHub top language](https://img.shields.io/github/languages/top/tooboi/gamma-ui?color=77B255&logo=sass&logoColor=77B255)

A clean, simple, and responsive CSS framework

- [Grid](#grid)
- [Flex](#flex)
- [Font](#font)
- [Spacing](#spacing)
- [Color](#color)
- [Buttons](#buttons)
- [Cards](#cards)

## Grid

### Columns

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

### Breakpoints

The column will be the set number of columns at that breakpoint and below

The classes are named using the format col-{breakpoint}-{numOfCols}

- sm - 576px

- md - 768px

- lg - 992px

- xl - 1200px

Examples

- col-sm-3

- col-md-5

- col-xl-4

## Flex


## Font

### Weight

The classes are named using the format fw-{weight}

- light - 300

- regular - 400

- medium - 500

- bold - 700

- black - 900

### Text Align

The classes are named using the format text-align-{alignment}

- text-align-left

- text-align-right

- text-align-center

- text-align-justify

## Spacing

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

- 1 - sets the margin or padding to 0.25rem
s
- 2 - sets the margin or padding to 0.5rem
s
- 3 - sets the margin or padding to 1rem
s
- 4 - sets the margin or padding to 1.5rem
s
- 5 - sets the margin or padding to 3rem

- m-auto - for classes that set the margin to auto

## Color

Colors are defined in the `:root` class at the beginning of the css file

## Buttons

Button format is created with `btn`

The color and style classes are named using the format btn-{outline}-{color}

outline variable is optional and will be a border only button

A button class would look like `btn btn-primary`

## Cards

Cards provide a surface to place your features to separate them from the background

Below is an example of how to use them

![Card](./images/Card.png)

```
<div class="container card">
  <div class="row justify-content-center">
    <h2 class="text-align-center">Card</h2>
  </div>
  <div class="row justify-content-center flex-wrap pb-3">
    <button class="btn btn-outline-primary mx-1">Max-Width</button>
    <button class="btn btn-primary mx-1">960px</button>
  </div>
</div>
```
