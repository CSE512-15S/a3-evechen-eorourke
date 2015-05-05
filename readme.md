a3-evechen-eorourke
===============

## Team Members

1. Yvonne Chen evechen@uw.edu
2. Nell O'Rourke eorourke@cs.washington.edu

## Data Visualization: Assignment 3

## The Dataset

- Number of Exercise Problems Completed: Students worked through exercise problems during class, either in their notebooks or on the tablets. We counted the number of these exercise problems each student completed, but did not grade the problems, since there were so many.

##Final Design

## Running Instructions
Access our visualization at http://cse512-15s.github.io/a3-evechen-eorourke/  or download this repository and run `python -m SimpleHTTPServer 8000` and access this from http://localhost:8000/.

## Story Board

[Click here to view our storyboard](storyboard.pdf?raw=true).

### Changes between Storyboard and the Final Implementation

Our original plan involved graphing by condition and generating bars by test type, but we realized that this combination was quite limited. Therefore, we added a set of buttons that changes the grouping of students to either a grouping by test type or by experimental condition. The two groupings have separate color to prevent visual confusion when switching between grouping types.

## Future Improvements

## Development Process

First, we met to brainstorm ideas for our visualization and storyboard our design.  After the storyboarding phase, Yvonne created an initial static mockup of our visualization design using D3 and JavaScript while Nell wrote scripts to format the Enlearn data and produce CSV files.  After the initial phase, we met to iterate on our design and plan out the interaction development.  Yvonne created the buttons for selecting the Unit and Test, and also wrote the code that handles hovering over bars using larger hit areas to make small bars more easily selectable.  Nell implemented code that handles clicking on bars and added the “Select All” and “Deselect All” buttons.  Nell also wrote the functionality to switch between the “Test Type” and “Condition” variables.  For the final write-up, Yvonne created the storyboard images and wrote a first draft of the write-up, and Nell filled in details about the data set and variables of interest. 

We spent around 25-30 hours developing our application, with coding taking up the majority of the time.