<h1># CSS layout project</h1>

<h2>$Navigation</h2>
  <li>In small screens, the site name and navigation items should appear stacked in one column.</li>
  <li>In large screens, the site name and navigation are laid out horizontally on the same line.</li>
  <li>The navigation links are laid out side-by-side, with margins between them.</li>
<h2>$Columns</h2>
  <li>The middle of the page has a centered content area.</li>
  <li>The center column should be the .primary-content column, which should be slightly wider than the other two columns.</li>
  <li>You can make the columns any width, as long as all three columns combined add up to a total width of 100%. For example, make the middle column 40% wide and the other two columns 30% wide.</li>
<h2>$Media Queries</h2>
  <li>You will use two media query breakpoints in the layout: the breakpoint at 769px, then determine at which resolution you need the next breakpoint to display all the three columns on the same line.</li>
<h2>$The Page Layout</h2>
  <li>The layout should be a fluid one-column layout in small screens, then a two-column layout in medium screens, and a fluid 3-column layout in large screens.</li>
  <li>It should use the 'mobile-first' approach you learned about in an earlier lesson.</li>
<h2>$Full-width header, footer, and banner</h2>
  <li>The <header> should have a container element that centers its content.</li>
  <li>The content inside the .banner and footer should be center-aligned center.</li>
  <li>The centered layout containers should be 80% wide on large screens, with a max-width of 1150px.</li>
  <hr>
<h2>$Create the Main Layout Containers</h2>
  First, you will create the layout containers (or wrappers) to center the layout on the page and keep it from looking too wide -- or too narrow -- depending on the device or viewport width.

  Include a container <div> that wraps the content inside the <header> element and one that wraps the three 'column' divs.
<hr>
<h2>$Add Media Queries for Large Screens</h2>
  Style the navigation and column layout for larger screens using media queries. The media queries should apply the styles when the viewport or device is 769px or wider.

  You should also give the '.container' element a width to prevent the layout from stretching too wide in larger screens. And use margins to center the layout in the browser.

<h2>$Style the .name and navigation elements</h2>
  Display the navigation list items side-by-side and create separation between each nav item. You may use a combination of both floats and inline-block to layout .main-nav the and navigation items inside.
<hr>
<h2>$Column Layout with Media Queries</h2>
  Display the columns side by side in medium and large screens, using floats. In the media query, float the columns left.

  HINT: At the 796px breakpoint, you should display only two columns side-by-side. Placing all three columns on the same line when the screen is 769px wide will make the columns appear too narrow on the screen, making the content difficult to read.

  Then define a second media query to write the column and container styles for a wider, 3-column layout. The breakpoint could be at at min-width of 1025px (when the viewport or device is 1025px or wider).

<h2>$Don't forget to clear the floats</h2>
  You'll notice that the floats for the .main-header and 'column' containers cause the containers' heights to collapse. Fortunately, you know the fix for this. The CSS already has a .clearfix rule you can apply to the collapsing containers.
