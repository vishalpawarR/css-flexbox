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
