# css-flexbox

Introduction to the CSS Flexbox Challenges

- A website's User Interface ("UI") has two components. First, there are the visual elements, such as colors, fonts, and images. Second, there is the placement or positioning of those elements. In Responsive Web Design, a UI layout must accommodate many different browsers and devices accessing the content.

- CSS3 introduced Flexible Boxes, or flexbox, to create page layouts for a dynamic UI. It is a layout mode that arranges elements in a predictable way for different screen sizes and browsers. While somewhat new, all popular modern browsers support flexbox. This section covers how to use flexbox and the different layout options it offers.

## 1 - Use display: flex to Position Two Boxes :

- This section uses alternating challenge styles to show how to use CSS to position elements in a flexible way. First, a challenge will explain theory, then a practical challenge using a simple tweet component will apply the flexbox concept.

- Placing the CSS property `display: flex;` on an element allows you to use other flex properties to build a responsive page.

- Add the CSS property `display` to `#box-container` and set its value to `flex`.

## 2 - Add Flex Superpowers to the Tweet Embed :

- To the right is the tweet embed that will be used as the practical example. Some of the elements would look better with a different layout. The last challenge demonstrated `display: flex`. Here you'll add it to several components in the tweet embed to start adjusting their positioning.

- Add the CSS property `display: flex` to all of the following items - note that the selectors are already set up in the CSS:

- `header`, the header's .`profile-name`, the header's `.follow-btn`, the header's `h3` and `h4`, the `footer`, and the footer's `.stats`.

## 3 - Use the flex-direction Property to Make a Row :

- Adding `display: flex` to an element turns it into a flex container. This makes it possible to align any children of that element into rows or columns. You do this by adding the `flex-direction` property to the parent item and setting it to row or column. Creating a row will align the children horizontally, and creating a column will align the children vertically.

- Other options for `flex-direction` are `row-reverse` and column-reverse.

> Note: The default value for the `flex-direction` property is `row`.

- Add the CSS property `flex-direction` to the `#box-container` element, and give it a value of `row-reverse`.

## 4 - Apply the flex-direction Property to Create Rows in the Tweet Embed :

- he `header` and `footer` in the tweet embed example have child items that could be arranged as rows using the `flex-direction` property. This tells CSS to align the children horizontally.

- Add the CSS property `flex-direction` to both the `header` and `footer` and set the value to row.

## 5 - Use the flex-direction Property to Make a Column :

The last two challenges used the `flex-direction` property set to `row`. This property can also create a column by vertically stacking the children of a flex container.

Add the CSS property `flex-direction` to the `#box-container` element, and give it a value of `column`.

## 6 - Apply the flex-direction Property to Create a Column in the Tweet Embed :

- The tweet embed `header` and `footer` used the `flex-direction` property earlier with a row value. Similarly, the items inside the `.profile-name` element would work well stacked as a column.

Add the CSS property `flex-direction` to the header's `.profile-name` element and set the value to column.

## 7 - Align Elements Using the justify-content Property :

- Sometimes the flex items within a flex container do not fill all the space in the container. It is common to want to tell CSS how to align and space out the flex items a certain way. Fortunately, the `justify-content` property has several options to do this. But first, there is some important terminology to understand before reviewing those options.

Here is a useful image showing a row to illustrate the concepts below.

Recall that setting a flex container as a row places the flex items side-by-side from left-to-right. A flex container set as a column places the flex items in a vertical stack from top-to-bottom. For each, the direction the flex items are arranged is called the main axis. For a row, this is a horizontal line that cuts through each item. And for a column, the main axis is a vertical line through the items.

There are several options for how to space the flex items along the line that is the main axis. One of the most commonly used is `justify-content: center;`, which aligns all the flex items to the center inside the flex container. Others options include:

- `flex-start`: aligns items to the start of the flex container. For a row, this pushes the items to the left of the container. For a column, this pushes the items to the top of the container. This is the default alignment if no `justify-content` is specified.
- `flex-end`: aligns items to the end of the flex container. For a row, this pushes the items to the right of the container. For a column, this pushes the items to the bottom of the container.
- `space-between`: aligns items to the center of the main axis, with extra space placed between the items. The first and last items are pushed to the very edge of the flex container. For example, in a row the first item is against the left side of the container, the last item is against the right side of the container, then the remaining space is distributed evenly among the other items.
- `space-around`: similar to `space-between` but the first and last items are not locked to the edges of the container, the space is distributed around all the items with a half space on either end of the flex container.
- `space-evenly`: Distributes space evenly between the flex items with a full space at either end of the flex container
  An example helps show this property in action. Add the CSS property `justify-content` to the #box-container element, and give it a value of `center`.

Bonus
Try the other options for the `justify-content` property in the code editor to see their differences. But note that a value of `center` is the only one that will pass this challenge.
