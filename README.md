# SassyStrings

Here is a [Compass Extension](http://compass-style.org/) providing you all functions you need to manipulate your [Sass](http://sass-lang.com/) strings.

## What's in there? 

* `str-count($string, $needle)`: counts number of occurrences of `$needle` in `$string`
* `str-explode($string, $separator)`: explodes `$string` on `$separator` occurrences 
* `str-implode($list)`: implodes `$list` into a string
* `str-last-index($string, $needle)`: returns last index of `$needle` in `$string`
* `str-lcfirst($string)`: turns first letter of `$string` into lower case
* `str-pad($string, $length, $pad: " ", $direction: left)`: pads `$string` with `$pad` to match `$length` starting from `$direction`
* `str-printf($string, $elements...)`: replaces occurrences of `%s` in `$string` by elements from `$elements`
* `str-repeat($string, $times)`: repeats `$string` `$times` times
* `str-replace($string, $old, $new: "", $case-sensitive: true)`: replaces `$old` by `$new` in `$string` respecting `$case-sensitive`
* `str-reverse($string)`: reverses string
* `str-rot($string, $rot: 13)`: rotates letters in `$string` of `$rot` position in alphabet
* `str-shuffle($string)`: shuffles letters in string
* `str-split($string)`: splits `$string` into a list of characters
* `str-trim($string)`: removes white spaces before and after `$string`
* `str-ucfirst($string)`: turns first letter of `$string` into upper case 
* `stringify($literal)`: casts to string

As well as default Sass core functions:

* `str-index`
* `str-slice`
* `str-length`
* `str-insert`
* `to-lower-case`
* `to-upper-case`

If you feel like an explorer, you can have a look at the code [here](https://github.com/Team-Sass/Sassy-Strings/tree/master/stylesheets).

## Requirements

* Sass ~> 3.3.0
* Compass ~> 1.0

Some functions depend on other functions. If you include functions individually, make sure to check for these dependencies in their respective docs.