# tt_cigscreensaver (TBA)
Modal that pops up after a set amount of idle time on the browser.

## HTML/CSS
- `overlay`: Translucent grey screen that fills full width and height of screen.
  - `content`: Black box with rounded corners, in the middle of `overlay`.
    - `cigarette`: Long rectangular div with no background, set in the middle of `content`.
      - `body`: Long rectangular div with no background.
        - `empty`: Rectangular div with no background, variable height.
          - `smokebubble`: Circular divs with varying `box-shadow`, `height`, `width`, `margin-top` and `margin-left` properties.
        - `burnable`: Rectangular div with linear white background.
          - `tip`: Small rectangular div at the top.
            - `ember`: Little rectangular divs with backgrounds that animate from red to orange.
      - `butt`: Short rectangular div with linear brown background.

## JavaScript
- `window.onLoad`
  - start the timer using `startTimer()`.
  - `keypress` or `mousemove`: `setLastActivity()` 
- `idleTimer`
  - `lastActivity`:
  - `msToPopup`:
  - xx
  - xx
  - xx
  - xx
  - xx
  - xx
  - xx
  - xx
  - xx
