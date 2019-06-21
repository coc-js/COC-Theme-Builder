


# COC Theme Builder
<p align="center">
  <img width="200" height="200" src="https://avatars2.githubusercontent.com/u/44804821?s=400&u=c2252c15889114f4fa1128f60b3156e9f1f2131e&v=4">
</p>

**Get Started**

Clone this repo and use the variables file so COC will build you many helpers based on your custom variables

 - Schema classes for backgrounds
 - Schema classes for text
 - Schema classes for borders
 - Borders classes
 - Margin classes
 - Padding classes

## Other Resources

**External resources**
 - [MaterializeCss - Grid System](https://materializecss.com/grid.html)
 - [MaterializeCss - Colors](https://materializecss.com/color.html)
 - [MaterializeCss - Shadow](https://materializecss.com/shadow.html)
 - [AnimateCss](https://daneden.github.io/animate.css/)
 - [Bulma - Buttons](https://bulma.io/documentation/elements/button/)
 
 **Resources By COC**
 - Typography Styles
 - Borders Styling and colors

## Quick Customization

In `/sass/themes/master/variables.scss` you will find the following schema
‘’’

    // Main Theme
$colors-list: (
// Primary
"primary": #2a0d45,
"light-primary": #f8bbd0,
"primary-alpha-first": rgba(233, 30, 99, 0.2),
"primary-alpha-half": rgba(233, 30, 99, 0.5),
"primary-alpha-end": rgba(233, 30, 99, 0.8),
"dark-primary":#880e4f,

// Secondary
"secondary":#fff,
// States **

// Info
"light-info": #e3f2fd,
"info":#2196f3,
"dark-info": #0d47a1,

// Success
"light-success": #e8f5e9,
"success":#66bb6a,
"dark-success": #388e3c,

// Warning
"light-warning": #ffd54f,
"warning":#ffc107,
"dark-warning":#ff8f00,

// Error
"light-error": #ef5350,
"error":#f44336,
"dark-error": #c62828,


// Typography
"title":#17233d,
"content":#515a6e,
"subColor":#808695,
"disabled":#c5c8ce,

// Bounds
"border":#dcdee2,
"dark-border":#9e9e9e,
"light-border":#fafafa,
"divider":#e8eaec,
"white":#ffffff,
"black": #000,
"carbon": #2d2e2e,
"light-background":#ffffff,
"background":#f8f8f9,
"dark-background":#e7e7e7,
"primary-background":#ffffff,
);
// Borders
$border-radius: (
	"none": 0px,
	"tiny": 3px,
	"standard": 5px,
	"rounded": 12px,
	"bounced" : 15px,
	"circle": 50%,
);
$typography-sizes: (
	// Pixels
	"tiny": 8px,
	"small": 12px,
	"normal": 15px,
	"normal-1": 17px,
	"normal-2": 20px,
	"large": 28px,
	"massive": 40px,
	"super": 74px,
	// Inhereted
	"xs": 50%,
	"sm": 80%,
	"md": 100%,
	"md-1": 110%,
	"md-2": 120%,
	"lg": 150%,
	"lg-1": 200%,
	"lg-2": 300%,
	// Points
	"title": 30pt,
	"subtitle": 20pt,
	"heading": 18pt,
	"body": 11pt,
);
$z-dimension: (
	"1": 0,
	"1-1": 10,
	"1-2": 20,
	"1-3": 30,
	"2": 100,
	"2-1": 110,
	"2-2": 120,
	"2-3": 130,
	"3": 1000,
	"3-1": 1100,
	"3-2": 1200,
	"3-3": 1300,
);
@function tint($color, $percentage) {
  @return mix(white, $color, $percentage);
}
@function shade($color, $percentage) {
  @return mix(black, $color, $percentage);
}
‘’’
Add your custom variables and compile the main sass file in your project, and you have your own custom theme!
