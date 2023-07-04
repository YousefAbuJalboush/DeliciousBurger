# Delicious Burger

## Design requirement:

- Using HTML and CSS only, design and code a burger image as follows:
  - The burger should consist of various components, including buns, lettuce, tomatos, cheese, and a patty. You are free to choose the design and colors for each component, but keep in mind that it should resemble a realistic burger.
  - The burger should be positioned at the center of the page.
- Implement responsiveness:
  - Ensure that the burger remains centered within the viewport as it increases in size.
  - When the viewport width is smaller than the specified breakpoint, the burger should adapt and remain fully visible within the smaller viewport.
  - Utilize appropriate CSS techniques to achieve responsiveness, such as media queries.

## Describe the CSS techniques:

- Flexbox: The display: flex; property is applied to the #burger-container element to create a flex container. This allows the child elements to be aligned horizontally and vertically.

- Media queries: Two media queries are used to define different styles based on the screen width. The @media rule is used to specify the conditions under which the styles should be applied. The first media query applies styles when the screen width is at least 425 pixels (min-width: 425px), and the second media query applies styles when the screen width is less than or equal to 425 pixels (max-width: 425px).

- Grid layout: Within each media query, the display: grid; property is applied to the #burger element. This allows the child elements to be arranged in a grid-like structure. The grid-gap property is used to define the gap between the grid cells.

- Keyframe animations: The @keyframes rule is used to define two animations, move-away, and move-back, which control the size and gap of the burger when hovered and when not hovered. These animations are applied to the #burger:hover and #burger:not(:hover) selectors respectively. The from and to keywords within the keyframes specify the starting and ending states of the animation.

- The vh unit is used for the height of the #burger-container to make it fill the full height of the viewport.
