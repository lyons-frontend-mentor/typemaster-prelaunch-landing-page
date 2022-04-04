# Design

## Components

- Nav bar
  - Logo
  - CTA
- Head
  - `h1`
  - Text
  - CTA
  - Release date
- Keyboard images
  - Top-down view
  - Side view
  - Orange filter
- Description
  - `h2`
  - Text
- Features
  - Four feature components, each consisting of:
    - Icon
    - `h3`
    - Description
- Footer
 
## Design system

### Colors

- Orange 600
  - Logo
  - CTA background in Head
  - Orange filtered keyboard image
  - Icons in Features
- Orange 300
  - Hover for CTA background in Head
- Blue-gray 700
  - Headings
  - Text for CTA in Nav bar
  - Hover background for CTA in Nav bar
- Gray 400
  - Background for CTA in Nav bar
  - Body text
- White
  - Text for CTA in Head
  - Text for CTA in Nav bar when hovered
  - Background for body

### Typography

- Barlow font; Black and Medium
- H1: Barlow Black, 56px - 56px, all caps
- H2: Barlow Black, 32px - 36px, all caps
- H3: Barlow Black, 24px - 28px, all caps
- Body: Barlow Medium, 16px - 26px

## Layouts

### Mobile

#### Distinguishing features

- `display: flex` with `flex-direction: column` for general layout.
- All text except in Head is center-aligned
- Keyboard images stacked one on top, two on bottom
- Top and left-bottom keyboard images are slightly cropped

#### Dimensions

- Body
  - mt-24
  - Everything centered except images
- Nav bar
  - 327 x 48
  - mb-64
  - Justified `space-between`
  - Aligned `center`
  - Logo
    - 40 x 40
  - CTA
    - 151 x 48
    - br-8
    - px-14 px-12
- Head
  - 327 x 286
  - Flex column
  - Text left-aligned
  - No padding
  - `h1`
    - mb-32
  - Text
    - mb-32
  - CTA
    - 310 x 48
    - Justified `space-between`
    - aligned `center`
    - px-14 px-12
    - mr-32
    - br-8
  - Release date
- Images
  - mb-72
  - Border radius 20 on all images
  - Top-view
    - 372 x 331
    - ml-24
    - mb-24
  - Side-view
    - 220 x 193
    - mr-24
  - Orange
    - 129 x 193
    - mr-24
- Description
  - 327 x 236
  - Text centered
  - mb-110
  - `h2`
    - mb-24
- Features
  - 327 x 297
  - Each component center aligned
  - mb-64
  - Last, mb-96
  - Logo
    - 65 x 65
    - mb-48
  - `h3`
    - mb-24
- Footer 
  - 272 x 26
  - Centered
  - mb-50

### Tablet

#### Distinguishing features

- Content no longer centered horizontally; now, left margin of 40
- Images now share space with Head, namely top-view
- Orange image no longer cropped
- Description flows horizontally instead of vertically
- Features make up a 2x2 grid

#### Dimensions

- Body
  - ml-40
  - mt-40
- Nav bar
  - 689 x 58
  - mb-64
  - Justified `space-between`
  - Aligned `center`
  - Logo
    - 40 x 40
  - CTA
    - 175 x 58
    - br-8
    - px-24 py-16
- Head
  - 339 x 305
  - Aligned with top-view image
  - Flex column
  - Text left-aligned
  - No padding
  - mr-125
  - `h1`
    - mb-32
  - Text
    - mb-36
  - CTA
    - 310 x 48
    - Justified `space-between`
    - aligned `center`
    - px-24 py-16
    - mr-36
    - br-8
  - Release date
- Images
  - mb-72
  - Border radius 20 on all images
  - Top-view
    - 478 x 425
    - mr-(-160)
    - mb-30
  - Side-view
    - 445 x 320
    - mr-125
  - Orange
    - 214 x 320
    - mr-32
  - Decorative rectangles
    - Margin of 32px on the corresponding side, go off screen
    - Border-radius 20
- Description
  - 327 x 236
  - Flex row
  - Text left-aligned
  - mb-142
  - mr-30
  - `h2`
    - mr-36
- Features
  - 281 x 289
  - Each component left-aligned
  - mb-72
  - mr-72 
  - Last, mb-144
  - Logo
    - 65 x 65
    - mb-40
  - `h3`
    - mb-24
- Footer 
  - 272 x 26
  - Centered
  - mb-50 

### Desktop

#### Distinguishing features

- Description now shares row with bottom images
- Max width with two decorative rectangles marking the vertical boundaries of the images
- Features all on one row

#### Dimensions

- Body
  - Max content width of 1110; outside this, only decorative rectangles; actual content centeredr
  - mt-55
- Nav bar
  - 1110 x 58
  - mb-84
  - Justified `space-between`
  - Aligned `center`
  - Logo
    - 40 x 40
  - CTA
    - 175 x 58
    - br-8
    - px-24 py-16
- Head
  - 445 x 312
  - Aligned with top-view image
  - Flex column
  - Text left-aligned
  - No padding 
  - `h1`
    - mb-32
  - Text
    - mb-36
  - CTA
    - 310 x 48
    - Justified `space-between`
    - aligned `center`
    - px-24 py-16
    - mr-36
    - br-8
  - Release date
- Images
  - mb-168
  - Border radius 20 on all images
  - Top-view
    - 540 x 480
    - mr-(-160)
    - mb-30
  - Side-view
    - 445 x 320
    - mr-30
  - Orange
    - 214 x 320
    - mr-32
- Description
  - 255 x 265
  - Flex column
  - Text left-aligned
  - mb-142
  - mr-40
  - `h2`
    - mr-36
- Features
  - 255 x 323
  - Each component left-aligned
  - mr-30
  - mb-128
  - Last, mb-144
  - Logo
    - 65 x 65
    - mb-48
  - `h3`
    - mb-24
- Footer 
  - 272 x 26
  - Centered
  - mb-50 
