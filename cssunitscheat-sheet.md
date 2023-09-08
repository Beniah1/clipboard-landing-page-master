Here are some common CSS properties and their responsive units explained:

height = vh (viewport height)
- Sets height relatively to viewport height 
- Allows element to be full screen height on different devices

width = % (percentage)  
- Sets width relatively to parent element
- Adjusts size automatically on different screen widths

max-width = rem (root em)
- Limits width relatively to root font size 
- Prevents stretching beyond a comfortable reading width

padding = em (relative to font-size)
- Padding resizes with text for consistent spacing
- Scales all elements predictably on different fonts   

margin = rem
- Keeps margins proportional to text 
- Consistent gutters for readability on any device

font-size = rem
- Sizes text based on root font 
- Text remains readable as user zooms or screen sizes change

By using relative units like vw, vh, %, em and rem instead of px, elements resize fluidly across all viewports for an adaptive user experience. This is key for building responsive websites.


Here is a CSS Units Cheat Sheet with some common responsive measurement units:

# CSS Units Cheat Sheet

## Viewport Units

- vw - Relative to 1% of viewport width
- vh - Relative to 1% of viewport height 

Works well for:
- Setting widths, heights 
- Full page layouts
- Media queries 

## Percentages  

- % - Relative to parent element width or height

Works well for: 
- Column widths
- Image sizes
- Self-resizing elements

## Rem

- rem - Relative to root/html font size

Works well for:
- Padding 
- Margins
- Font sizes
- Overall layout proportions

## Em

- em - Relative to element's font size

Works well for:
- Text sizes inside parent  
- Margins 
- Padding

## Other Units

- px - Pixels, fixed size not recommended
- pt - Points - Print units  
- in - Inches
- cm - Centimeters
- mm - Millimeters

By choosing relative units over fixed, elements can fluidly resize and spacing remains consistent for any device or font size. This ensures responsive designs.