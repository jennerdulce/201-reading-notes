## HTML

### Ch 4. Links
- `<a href="URL">text goes here</a>`
- `target="_blank"`
- `<a href="mailto:johndoe@email.com">email</a>`
- Absolute URL (Universal Resource Locator)
  - includes https://
- Relative URL
  - index.html (local document)
  - google.com (missing https://)

#### Structure
- top level folder is known as "root"
- Relationships based on Family Tree
  - Root folders contain "index.html" and individual/child folders
  - each sub directory contains index.html which is a homepage
  - Same folder: doc.html
  - child folder: folder/doc.html
  - grandchild: folder/folder/doc.html
  - parent: ../document.html
  - g-parent: ../../document.html

#### Linking to Different Parts of a Page
- set id=" " for locations you want to link
  - `<a href="#idtag"></a>`
  - id attributes to identify specific parts of the page that you want to JUMP to
  - combind to get the bottom of a new page
  - `<a href="http://website.com/#bottom"></a>

## CSS
### Ch 15. Layout
- screen sizes
  - it is often that you will have visitors using varous screen sizes
  - iPhone: 960 x 640
  - iPad: 1024 x 760
  - MacBook: 1280 x 800
  - 27" iMac: 2560 x 1440
- **Create webpages 960-1000 px wide**
  - usability studies have shown that visitors can judge a page in under a page in under a second
  - it is important to let new visitors know that the site is relevant to them and their interests

#### Fixed Width Layout
- does not change sizes when user increases/decreases size of their browser window
  - measure given in **PIXELS**
- will stay the same width no matter what
- **when floating items on the same line**
  - must be **split evenly** of total width of body/container
  - margin/padding take up pixel space of the width

- **--PROS--**
- accurate pixel values
- designer has greater control, because everything is set/fixed
- consistent between all platforms
- image sizes will always remain the same

- **--CONS--**
- big gaps on sides of the screen
- screens w/ highers resolution makes smaller text
- often take up more vertical space

#### Liquid Layouts
- stretch and contract as user increases and decreases browser window
- uses **PERCENTAGES**
- `overflow: auto;` is always good to have
- `width: 90%`
- widths of float elements should be split evenly between 100%
  - `margin: 1%` to help align columns that are side by side
  - `width: 33.3%` columns
- `min-width` and `-max-width` help to create boundaries to set a limit of stretching/sizing due to window sizing

- **--PROS--**
- fill entire screen
- page can contract to fit screen without user scrolling to sides
- tolerant font sizes

- **--CONS--**
- Wide windows make fonts hard to read
- narrow may be squashed images can end up overflowing/spilling

#### Layout Grids
- Composition
  - placement or arrangements of visual elements/how they are organized on a page
  - designers and web designers use grids
- **960 px grid**
  - consistent proportions between items and gives a professional look.
  - creates continuity between different pages
  helps users navigate
  - easier to add new content
  - help with collaborations


## JavaScript

### Ch 3. Functions, Methods, Objects


### Article: "6 Reasons for Pair Programming"


## Lecture