# Training - CSS - Flex Box

## Instructions
  - Use the two `.html` files, one for each style of image gallery
  - Each file should be a gallery of image previews, [similar to those seen on many websites](https://www.tooplate.com/html-templates/2086-multi-color.jpg)
  - Each file should use only standard HTML and CSS to meet the objectives
  
## Objectives

### Old-Style Gallery

  - Create a gallery of square images WITHOUT using CSS flex box or CSS grid
  - Each image slot should be the same width and height, regardless of source image size
  - Images should "cover" the space (ie. zoom + crop, as necessary to avoid extra whitespace)
  - Images should have a small gutter between them
  - Grid should have no gutters on the outside edges (very top, bottom, left and right of the whole grid)
  - Grid should start in the top left and move to the bottom right as more images are presented
  - Grid should accept an arbitrary number of images
    - If there aren't enough images to fill the page, images should start at the left and move right without extra gutter between them (ie. put any extra whitespace to the right and/or below the images)

### Flex Gallery

  - Create a gallery of square images using CSS flex box
  - Each image slot should have the same max width and max height, but should match the source image aspect ratio
  - Images should "fit" the space (ie.  no zooming or cropping, extra whitespace is allowed)
  - Images should be centered horizontally and vertically inside their slots
  - Images should have a small gutter between them
  - Grid should have no gutters on the outside edges (very top, bottom, left and right of the whole grid)
  - Grid should start in the top left and move to the bottom right as more images are presented
  - Grid should accept an arbitrary number of images
    - If there aren't enough images to fill the page, images should start at the left and ove right without extra gutter between them (ie. put any extra whitespace to the right and/or below the images)

## Resources

  - [Unsplash](https://source.unsplash.com/): Random image URLs
  - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [Negative Margins](https://css-tricks.com/negative-margins/)

## Notes
  - HTML `<img>` tags can be a bit squirly to size and layout. It's usually best to wrap each image in a container `<div>` and apply the sizing and layout to that div.
