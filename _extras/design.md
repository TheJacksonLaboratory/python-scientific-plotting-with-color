# Scientific plotting with Color in Python

## Assumptions

-   Audience
    -   Graduate students, post docs, research associates, one or two PIs or
        advanced stage researchers
    -   Backgrounds in biology, bioinformatics
    -   Novice to intermediate Python programming skills
    -   Active users of some form of data analysis program (Excel, Prism, R,
        SAS, Stata, etc.)
    -   Have generated basic figures before in Excel, R, or Python.

-   Constraints
    -   2 full days
    -   12:45 of teaching time

-   Focus on matplotlib functionality
    -   Will introduce pandas and seaborn functionality, but focus on teaching
        how to use matplotlib primitives (it's easy to use those other tools,
        but they are built on top of matplotlib and knowing some fundamentals
        helps immensely in terms of customization).
    -   Stick with `pyplot` oriented styling, not introducing `pylab` at all.
    -   Most people, even those with heavy experience with matplotlib, are not
        masters of the subject and likely have many gaps in understanding
        relationships between library objects and the overall design behind the
        library

-   Introduce plotting tools first, then how to use them effectively
    -   Day 1 will focus on matplotlib and the different types of plotting
    -   Day 2 will spend half the day discussing benefits of certain plots over
        others and half the day on using color effectively.

-   Data
    -   [TODO] no idea which dataset to use yet

-   Many short examples

## Desired results

Users will learn to
-   generate basic graphics with Python
-   customize plots in Python
-   construct multi-panel plots
-   choose what type of plot to make given dataset
-   use discrete colors effectively
-   correctly use colormaps for plotting continuous data

## Learning Plan

### Summative assessment
-   After day 1:  create a multi-panel plot with axes labels, subplot panels, and
    multiple plot types
-   After day 2:
    -   be given a new data set and generate a multi-panel plot containing most
        suitable graphics to show specific trends (boxplot, scatter with
        discrete color, diverging-scale colorbar)
    -   be given problematic graphics to identify and suggest alternatives to
        correct problems

## Day 1 (9:00 am - 5:00 pm)

### Introduction to the tools - Part 1 (9:15 am - 12:00 pm)
Teach the structure and function behind matplotlib basics
-   Relationship between Figures, Axes, and Axis
-   General structure of matplotlib syntax (may not know the name a function but
    learn to make good educated guesses and know where to find the answer)
-   How to annotate figures and axes with text
-   How to change the axes limits, ticks, aspect
-   Multi-panel plotting

#### Running Jupyter notebooks and Help (9:15 am)

#### Matplotlib fundamentals - Figures and Axes objects (9:30 am)

#### Matplotlib fundamentals - Figure and Axes labels (10:00 am)

#### Break (10:20 am)

#### Matplotlib fundamentals - Figure and Axes viewport manipulation (10:30 am)

#### Matplotlib fundamentals - Subplots (10:50 am)

#### Matplotlib fundamentals - Available plotting functions (11:30 am)

#### Lunch (12:00 pm)

### Introduction to the tools - Part 2 (1:00 pm - 2:30 pm)
-   Learn about tools built on top of matplotlib that extend its functionality
-   Observe pros and cons of using additional libraries
-   Learn how to use matplotlib to change returned graphics from seaborn and
    pandas

#### Pandas DataFrames (1:00 pm)

#### Pandas and Matplotlib Union - Plotting with dataframes (1:30 pm)

#### Seaborn (2:00 pm)

#### Tweaking seaborn and pandas figures (2:30 pm)

#### Break (3:00 pm)

### How data informs plot type (3:15 pm - 5:00 pm)
-    Between this session and first session of the following day, want to show
     why certain graphics are problematic.
     -   Teach best ways to represent certain data structures visually
          **first**
     -   Then the next day specifically show why certain visualizations are
         problematic.  Because we showed the benefits of the correct
         visualizations, they should have the tools and understanding to see why
         highlighted graphics are problematic.

#### Plotting categorical data (3:15 pm)

#### Plotting two-dimensional data (3:45 pm)

#### Plotting three-dimensional data in two dimensions (4:15 pm)

#### Assessment and feed back (4:45 pm)


## Day 2 (9:00 am - 4:30 pm)

### Correcting bad plotting habits (9:15 am - 12:00 pm)
-   Use previous day's lesson to motivate why:
    -   Pie and area charts are universally bad
    -   Venn diagrams are often problematic
    -   barcharts are often misused and boxplots/violin plots are substantially
        more informative in those cases.

#### Pie and area charts (9:15 am)

#### Venn diagrams (9:45 am)

#### Break (10:30 am)

#### Bar charts (10:45 am)

#### Lunch (12:00 pm)

### How to effectively use color in visualizations (1:00 pm - 4:30 pm)
Want students to learn:
-   What is a colormap and what is its purpose
-   How colormaps aid in the visual display of data, and how poor colormap
    choices can mislead that display
-   What are the properties of a good continuous colormap
-   How to choose effective colors for discrete palettes
-   Where to find more information about colormap best practices
-   When and where color is (not) needed in visualizations
-   Some general info about colorblindness and how to make publication images
    more colorblind friendly.

#### Introduction to colormaps (1:00 pm)

#### How colormaps affect data interpretation (1:20 pm)

#### Properties of good colormaps (1:50 pm)

#### Discrete colormaps and palettes (2:20 pm)

#### Resources for colormap information (2:50 pm)
-   ColorBrewer2
-   Colorspacious
-   cmocean

#### Using colormaps and palettes effectively (3:00 pm)

#### Colorblindness (3:45 pm)

#### Final assessment (4:10 pm)
