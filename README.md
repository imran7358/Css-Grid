  <code style="font-size:14px">Css Grid is a two-dimensional layout System</code> with the using of row and column.
  <h2 style="margin:20px 0">Layout Mode</h2>
  <p style="font-size:14px">Before Css there were 5 lyout model</p>
  <ol>
  <li><code>Block</code>for a block element its cover a block</li>
  <li><code>Inline</code>for a inline element showing element in sigle line.</li>
    <li><code>Table</code>for tow-dimensional tabular data</li>
  <li><code>Positions</code>for the explicit position of an element</li>
   <li><code>Flexbox</code>one-dimensional grid layout</li>
  </ol>
<h2 style="margin:20px 0">Pre-Css Grid we have used :</h2>
<ul>
<li>Different positional properties like <code>fixed, absolute</code> to set alignment at the exact required place</li>
<li><code>Floats and clear fixes </code>to create navigation, detailed section</li>
<li>Fixed heights columns to show equality</li>
<li>Above mentioned layout modes does not provide enough flexibility to create/build or design professional/nested/modern layouts</li>
<li>we need to include another CSS mechanism like Floats, Vertical alignment of text/elements and other hacks with Margin, Padding to create the accurate/desired layout</li>
<li><code>CSS Flexible Box Layout Module (Flexbox),</code> makes it easier to design flexible responsive layout structure without using float or positioning</li>
</ul>
<h2 style="margin:20px 0">Why CSS Grid?</h2>
<p>Grid/CSS Grid Layout provides lots of flexibilities while creating complex layouts like:</p>
<ul>
  <li>CSS Grid is a new way of creating layouts, the first time a proper layout system available natively in the browser with tons of benefits</li>
  <li>Grid is a new CSS display type designed to craft CSS layouts in a much easier way</li>
  <li>No CSS Float used</li>
  <li>Offers ultimate flexibility to create complex layouts without using extra markup or containers or floats</li>
  <li>Helps to create a nested Grid layout and place them on a webpage</li>
  <li>Arrange items from left to right or top to bottom and vice versa</li>
  <li>Adjust the spacing between objects</li>
  <li>Position and alignments of items</li>
  <li>Order and placements of various elements</li>
  <li>Improve the items alignment, directions and order in the container even when they are with dynamic or even unknown size</li>
  <li>Equal height columns</li>
  <li>Ability to modify the width or height of its children to fill the available space in the best possible way on different screen sizes</li>
  <li>Control the position, size, and spacing of child elements relative to parent container and other child elements</li>
  <li>CSS Grid works great responsively (RWD - Responsive Web Design)</li>
  <li>Responsive and Mobile friendly</li>
</ul>
<h2 style="margin:20px 0">Browser support</h2>
<p>The CSS Grid properties are supported in all modern browsers:</p>
<h2 style="margin:20px 0">CSS Grid Layout Properties</h2>
<ul>
  <li><code><strong>display:grid</strong></code> (CSS property/style which converts an HTML element to a grid container <code><em>- display: grid or inline-grid<em></code>)</li>
    <li>
      <code><strong> Grid Container</storng></code> (Direct Parent/Container to hold sub-items, to the container we apply <code><em>display: grid or inline-grid</em></code> property)
    </li>
    <li><code><storng>Grid Items</storng></code> (Child/sub-items [direct descendants] within Container - All direct children of the <code>grid container</code> automatically become <code>grid items</code>)</li>
    <li>
      <code><strong>Grid Column</strong></code> (The vertical series-part/portrait lines of the grid, table, chart or spreadsheet. CSS property is <code>grid-template-columns</code>)
    </li>
    <li><code><strong>Grid Row</strong></code> (The horizontal series-part/landscape lines of the grid, table, chart or spreadsheet. CSS property is <code>grid-template-rows</code>)</li>
    <li><code><srong>Grid Gaps</strong></code> (The spaces (margin or cell-spacing) between each column/row. CSS property is <code>grid-column-gap</code> and <code>grid-row-gap</code>)</li>
    <li><code><strong>Grid Line </strong></code>(The lines between columns/rows, the dividing lines that make up the structure of the grid. CSS property is <code><em>grid-column-start</em></code> , <code><em>grid-column-end</em></code> and <code><em>grid-row-start</em></code>, <code><em>grid-row-end</em></code>)</li>
    <li><code><strong>Grid Track </strong></code>(A grid track is a space between 2 adjacent grid lines, they are the rows and columns of your grid)</li>
    <li><code><strong>Grid Cell</strong></code> (A box/intersection point where the column and row get insects it creates a box/cell like a table cell, A grid cell is the space between 2 adjacent row grid lines and 2 adjacent column grid lines)</li>
    <li><code><strong>Grid Area</strong></code> (The total space surrounded by four grid lines, A grid area is made up of 1 or more grid cells, and is bound by 4 grid lines on each side of the grid area. CSS property is grid-item = grid-area, grid-container = grid-template-areas)</li>
    <li><code><strong>The fr Unit </strong></code>(The new <code><em>fr unit (fractional unit)</em></code> represents a fraction of the available space or free space available in the grid container. Simply available space is nothing but free space so you can also consider fr as free space. CSS property is <code><em>grid-template-columns/rows: 1fr 1fr 1fr</em></code>)</li>
    <li>
      <code><strong>Explicit Column/Row</strong></code> Any Column or Row created as per needs and requirements with property <code><em>grid-template-columns</em></code> and <code><em>grid-template-rows</em></code> respectively (Explicit = Developer or User defines how many Columns or Rows required)
    </li>
    
    <li><code><em>Implicit Column/Row </em></code> Auto-generated Column/Row. grid-auto-columns and grid-auto-rows property used to handle/control/size any auto-generated grid tracks ie. implicit grid (Implicit = Automatically generated Column/Row. [Total Grid Items are 10, we defined 2 columns and 2 Rows with grid-template-columns and grid-template-rows property, so 4 items are Explicit and rest 6 items are Implicit])</li>
    
</ul>
