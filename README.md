# CG_condor_tutorial_macros
Assorted macros for processing CrystalGrower data from grep output.


Merge CSVs will merge all .csv files selected into one workbook, each file on a separate sheet.
Merge space will do the same for files where values are separated by spaces.

Combine and plot - all macros marked with combine will allow users to combine .csv files first then automatically plot column x vs. any number of columns y.
Points will plot as points, no trendline will be lines without trendlines.

All macros marked with "all" will process a merged workbook - going through each sheet and automatically plot column x vs. any number of columns y.

All macros marked with "one" will automatically plot column x vs. any number of columns y for only the current sheet.

Auto plot 3D will create a 3D plot for one worksheet.
Combine and plot 3D will combine .csv files into one workbook, on separate sheets and plot 3D graphs for each.

Some macros have dependencies on others so it's best to copy all of them.
