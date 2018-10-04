# Data Visualization Projects: Visualize Data with a Bar Chart for freecodecamp.org

### Build a Bar Chart with D3

#### Objective

Build a CodePen.io app that is functionally similar to this: https://codepen.io/freeCodeCamp/full/GrZVaM.

#### Fulfill the below user stories and get all of the tests to pass. Give it your own personal style. You can use HTML, JavaScript, CSS, and the D3 svg-based visualization library. The tests require axes to be generated using the D3 axis property, which automatically generates ticks along the axis. These ticks are required for passing the D3 tests because their positions are used to determine alignment of graphed elements. Required (non-virtual) DOM elements are queried on the moment of each test. If you use a frontend framework (like Vue for example), the test results may be inaccurate for dynamic content. We hope to accommodate them eventually, but these frameworks are not currently supported for D3 projects.

1. User Story: My chart should have a title with a corresponding id="title".
2. User Story: My chart should have a g element x-axis with a corresponding id="x-axis".
3. User Story: My chart should have a g element y-axis with a corresponding id="y-axis".
4. User Story: Both axes should contain multiple tick labels, each with the corresponding class="tick".
5. User Story: My chart should have a rect element for each data point with a corresponding class="bar" displaying the data.
6. User Story: Each bar should have the properties data-date and data-gdp containing date and GDP values.
7. User Story: The bar elements' data-date properties should match the order of the provided data.
8. User Story: The bar elements' data-gdp properties should match the order of the provided data.
9. User Story: Each bar element's height should accurately represent the data's corresponding GDP.
10. User Story: The data-date attribute and its corresponding bar element should align with the corresponding value on the x-axis.
11. User Story: The data-gdp attribute and its corresponding bar element should align with the corresponding value on the y-axis.
12. User Story: I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
13. User Story: My tooltip should have a data-date property that corresponds to the data-date of the active area.

#### Here is the dataset you will need to complete this project: 
* https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json
