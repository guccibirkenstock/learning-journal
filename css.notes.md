# CSS
- CSS allows us to style whole blocks, or sections of html script
- CSS rule contains two parts
> 1. selector: indicates which element the rule applies to. The same rule can apply to multiple elements, but you *must seperate eachelement name with a comma* {p}
> 2. declaration: indicates how the elements referred to in the selector should be styled.  Split into two parts, the *property* and *value*
property: indicates the aspects of the elements you want to change (ex. color, font, width, height etc.){font-family}
value: specify the settings you want to use for the chosen properties (ex. specify color, font size value etc.){Arial}
```
EXAMPLE
p{
  font-family: Arial;}
```
##### If there are two or more rules that apply to the same element...
- if the two selectors are identical, the latter of the two will take precedence
- if one selector is more specific than the others, the more specifi c rule will take precedence
- you can add `!important` after any property value to indicate that it should be considered more important than the other rules that apply to the same element

### Color
- 3 ways to specify color: RBG values, hex codes, color names
- CSS treats each HTML element as if it appears in a box
- `background-color` property sets the color of the background *for that box*
```
ex
body {
background-color: rgb(200,200,200);} 
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
```
- if you do not set a backround color, then the background is transparent

### Opacity
value is a number between 0.0 and 1.0 and relates to % opacity
```
p.one {
background-color: rgb(0,0,0);
opacity: 0.5;}
```
