## Key CSS properties

- body css
  - clear body margin and padding
  - import fonts and set font-family to body
  - box-sizing: border-box, so that we can use width and height to control the size of the element
  - set min-height to 100vh, to make sure the footer is always at the bottom of the page
  - set position to be relative, so that we can use absolute position to position the container
  - set background-size to contain, so that the background image will be scaled to fit the container
- container css
  - set position to be absolute, so that we can use top, left, right, bottom to position the container. left 50%, top 50% will make the container centered, transform: translate(-50%, -50%) will make the container centered in the browser
  - set overflow to be hidden, so that the background image will not overflow the container
  - set border-radius to 20px, so that the container will have rounded corners
- .text-content class

  - .title: add color, font-weight, font-size, margin-bottom
  - .subtitle: choose lighter color than pure black.
  - .plan-box: background color to be very pale blue. display flex, set justify-content to space-between
    - The "Change" anchor tag have bold font-weight, color to be very dark blue, when hover, color to be bright blue and text-decoration to be none, add transition to color to be color 0.3s ease
  - .proceed-btn: background color to be bright blue, color to be white, border-radius to be 10px, padding to be 20px 0px, margin to be 30px 0px. When hover, background color to be Desaturated blue, add transition to background-color to be background-color 0.3s ease
  - .cancel.btn: background color to be very pale blue, text-decoration to be none, font-weight to be bold 900. When hover, background color to be dark blue

- add responsive design for mobile and desktop
  - add media query for screen width less than 425px
    - set body font-size to be 14px
    - container to be max-width 90%
    - smaller title font-size
    - smaller plan box padding
    - smaller text font of anchor tag
    - less padding for anchor tag button
