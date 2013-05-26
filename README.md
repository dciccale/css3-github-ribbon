# CSS3 Github Ribbon

Use this CSS3 Github Ribbon on your github-based projects, it's fully customizable!

## Usage

Just link `css3-github-ribbon.css` on your html document and paste the github link on it:

```html
<a href="https://github.com/dciccale/css3-github-ribbon" class="github-ribbon">Fork me on GitHub</a>
```

### [Live demo](http://dciccale.github.com/css3-github-ribbon/)

## Options
You will need [Stylus](http://learnboost.github.com/stylus/) and [Node.js](http://nodejs.org/) to compile the modified `.styl` file

### Background color
Change the `$bgcolor` variable to any valid CSS color.

```php
$bgcolor papayaWheep
```

#### Text color
Change the `$color` variable to any valid CSS color.

```php
$color #222
```

#### Position
Change the `$position` variable to one of these two values: 'top-right' (default) or 'top-left'.

```php
$position 'top-right'
```

### Known issues and fixes
 - Unintended horizontal scrolling can cut the edges of the ribbon

To fix this add the following code to the .styl file
```
body
  overflow-x none
```

## License
See [LICENSE.txt](https://raw.github.com/dciccale/css3-github-ribbon/master/LICENSE.txt)
