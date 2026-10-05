# Excel Topics Index
(Generate via Claude)
---

## 1. Data and Its Types
1.1 **Qualitative (Categorical) Data** — non-numeric labels — colors, feedback, departments.
1.2 **Quantitative Data — Discrete** — countable whole numbers only — e.g. number of employees.
1.3 **Quantitative Data — Continuous** — can take decimal values — e.g. height, purchase amount.
1.4 **Structured Data** — organized in tables/databases — spreadsheets, SQL records.
1.5 **Unstructured Data** — no predefined format — emails, social posts, video/images.
1.6 **Excel's Native Storage Formats** — Text, Number, Date & Time, Boolean — how the above ultimately get stored in a cell.

## 2. Excel Basics
2.1 **Workbook, Worksheet & Cell Structure** — how the file, tabs, and rows/columns relate.
2.2 **Opening & Navigating Excel** — the Ribbon and the Formula Bar.
2.3 **Basic Data Entry** — typing into cells; Enter moves down, Tab moves right.
2.4 **Simple (Manual) Formulas** — arithmetic like `=50+70`.
2.5 **Using Functions** — built-in shortcuts like `=SUM(B2:B4)`.
2.6 **Cut, Copy & Paste** — Ctrl+X / Ctrl+C / Ctrl+V, plus Paste Special (values only).
2.7 **Undo & Redo** — Ctrl+Z / Ctrl+Y.
2.8 **Fonts & Alignment** — Home tab text formatting controls.
2.9 **Number Formatting** — General, Number, Currency, Percentage, Date.
2.10 **Sorting & Filtering** — organizing and narrowing down data.
2.11 **Saving Files** — Save vs Save As; formats .xlsx / .csv / .xlsm.
2.12 **Exporting to PDF** — File → Export → Create PDF/XPS.
2.13 **Core Keyboard Shortcuts** — Ctrl+S, Ctrl+C, Ctrl+V, Ctrl+Z, Ctrl+Shift+V.

## 3. Formulas and Functions
3.1 **Formula vs Function** — user-built calc (`=A1+B1`) vs Excel's predefined calc (`=SUM(A1:A5)`).
3.2 **Formula Syntax Rules** — always starts with `=`; functions follow `=NAME(arg1, arg2, ...)`.
3.3 **Mathematical Functions** — SUM, PRODUCT, ABS — arithmetic operations.
3.4 **Statistical Functions** — AVERAGE, COUNT, MAX, MIN — summarizing numbers.
3.5 **Logical Functions** — IF, AND, OR, NOT — decision-making in a cell.
3.6 **Lookup Functions (intro)** — VLOOKUP, HLOOKUP, INDEX, MATCH — searching for data.
3.7 **Text Functions** — LEFT, RIGHT, CONCATENATE, LEN — manipulating text.
3.8 **Date & Time Functions** — TODAY, NOW, YEAR, MONTH — working with dates.

## 4. Tracing Precedents & Dependents
4.1 **Precedents** — cells that feed INTO a given formula.
4.2 **Dependents** — cells that USE a given formula's result.
4.3 **Trace Precedents / Trace Dependents** — Formulas tab → draws blue arrows for auditing.
4.4 **Removing Tracer Arrows** — Formulas → Remove Arrows.
4.5 **Error-Checking with Tracing** — using arrows to catch #REF! errors and broken/circular references.

## 5. Consolidating Data
5.1 **What Consolidation Does** — merges data from multiple sheets/workbooks into one summary.
5.2 **Choosing the Summary Function** — Sum, Average, Count, Max, Min, etc.
5.3 **Consolidating Across Sheets** — Data → Consolidate → Add ranges from each sheet.
5.4 **Consolidating Across Workbooks** — same process, using Browse to pull ranges from other files.
5.5 **Using Labels for Structured Merging** — Use Labels in Top Row / Left Column for auto-matching.
5.6 **Static vs Linked Consolidation** — "Create Links to Source Data" makes it update automatically; otherwise it's a snapshot.

## 6. Named Ranges
6.1 **What a Named Range Is** — a meaningful name assigned to a cell/range, e.g. SalesData for B2:B4.
6.2 **Creating a Named Range** — select range → type name in the Name Box, or Formulas → Define Name.
6.3 **Naming Rules** — no spaces, must start with a letter, can't be an Excel keyword.
6.4 **Using Named Ranges in Formulas** — `=SUM(SalesData)` instead of `=SUM(B2:B4)`.
6.5 **Editing / Deleting** — Formulas → Name Manager (Ctrl+F3).
6.6 **Dynamic Named Ranges** — OFFSET + COUNTA formulas so the range auto-expands with new data.

## 7. Insert Table & Style Options
7.1 **What a Table Is** — a structured range with built-in sort/filter, formatting, and auto-expansion.
7.2 **Inserting a Table** — Ctrl+T, or Insert → Table.
7.3 **Table Components** — Header Row, Banded Rows, Total Row, Sort & Filter buttons.
7.4 **Applying Table Styles** — Table Design → Table Styles.
7.5 **Enabling the Total Row** — Table Design → Total Row → choose SUM/COUNT/AVERAGE per column.
7.6 **Structured References** — `=SUM(Table1[Sales])` — auto-updates as rows are added.
7.7 **Converting Table Back to Range** — Table Design → Convert to Range (keeps formatting, loses auto-expansion).

## 8. Charts & Graphs
8.1 **Why Visualize Data** — spotting trends, comparisons, and outliers faster than raw numbers.
8.2 **Column Chart** — comparing values across categories.
8.3 **Bar Chart** — horizontal comparisons, good for long category names.
8.4 **Line Chart** — trends over time.
8.5 **Pie Chart** — parts of a whole, ideally ≤5 categories.
8.6 **Scatter Plot** — relationship between two variables.
8.7 **Area Chart** — cumulative trend over time.
8.8 **Histogram** — frequency distribution.
8.9 **Creating & Customizing a Chart** — Insert → choose type → edit title/labels/colors/layout.

## 9. AutoFill & Flash Fill
9.1 **AutoFill — Copy Cells** — repeats the same value across a selected range.
9.2 **AutoFill — Fill Series** — extends a sequence: 1,2,3… or Jan, Feb, Mar…
9.3 **AutoFill — Fill Formatting Only** — copies formatting without changing values.
9.4 **AutoFill — Fill Without Formatting** — copies values but ignores formatting.
9.5 **Flash Fill — Pattern Recognition** — Ctrl+E; learns a pattern from your first typed example.
9.6 **Flash Fill — Splitting Text** — e.g. extracting first names from full names.
9.7 **Flash Fill — Combining Text** — e.g. merging first + last name into one column.
9.8 **Flash Fill's Static Nature** — results don't auto-update if source data later changes.

## 10. Cell Styles, Basic IF & Conditional Formatting
10.1 **Cell Styles** — Home → Cell Styles → quick predefined formatting (Good/Bad/Neutral/Heading).
10.2 **The IF Function** — `=IF(condition, value_if_true, value_if_false)` — single logical test.
10.3 **Conditional Formatting — Highlight Cell Rules** — Greater Than / Less Than / Equal To, etc.
10.4 **Conditional Formatting — Color Scales** — gradient shading based on value.
10.5 **Conditional Formatting — Data Bars** — in-cell horizontal bars representing magnitude.
10.6 **Conditional Formatting — Icon Sets** — arrows/traffic lights classifying values.

## 11. Advanced Conditional Formatting
11.1 **Formula-Based Rules** — custom logic via a formula, e.g. `=B2=TODAY()`.
11.2 **Icon Sets (Advanced Use)** — custom thresholds for arrows/traffic lights.
11.3 **Color Scales (Advanced Use)** — multi-point gradients for nuanced visualization.
11.4 **Data Bars (Advanced Use)** — comparing magnitudes at a glance across a column.
11.5 **Managing Multiple Rules** — rule priority order and "Stop If True" behavior.

## 12. Nested IF & IFERROR
12.1 **Nested IF** — an IF inside another IF, for multiple result tiers (e.g. grading).
12.2 **IFERROR** — `=IFERROR(expression, value_if_error)` — replaces ANY error with a custom message.
12.3 **IFNA** — catches only #N/A errors — safer when you don't want to mask other bugs.
12.4 **IFERROR with VLOOKUP** — handling missing lookup values gracefully.
12.5 **Combining Nested IF + IFERROR** — wrapping a tiered IF formula so invalid input shows a clean message.

## 13. Advanced SUM & COUNT Functions
13.1 **SUMIF** — adds values based on a single condition.
13.2 **SUMIFS** — adds values based on multiple conditions.
13.3 **COUNTIF** — counts values based on a single condition.
13.4 **COUNTIFS** — counts values based on multiple conditions.
13.5 **SUBTOTAL** — summary stats that ignore hidden/filtered rows.

## 14. Lookup Functions
14.1 **VLOOKUP** — vertical search; lookup column must be leftmost.
14.2 **HLOOKUP** — horizontal search; lookup row must be topmost.
14.3 **LOOKUP** — legacy function, requires sorted data.
14.4 **INDEX** — returns a value from a specific row/column position.
14.5 **MATCH** — returns the position of a value within a range.
14.6 **INDEX + MATCH (combined)** — flexible alternative to VLOOKUP — works in any direction.
14.7 **XLOOKUP** — modern all-in-one replacement (Excel 365+), any direction, built-in error handling.

## 15. Data Validation
15.1 **Whole Number Rule** — restricts entry to integers within a range.
15.2 **Decimal Rule** — restricts entry to decimal values within a range.
15.3 **List Rule (Dropdown)** — restricts entry to a predefined set of choices.
15.4 **Date & Time Rule** — restricts entry to a valid date/time range.
15.5 **Text Length Rule** — limits number of characters allowed.
15.6 **Custom Formula Rule** — advanced logic, e.g. checking for "@" in an email field.

## 16. PivotTables
16.1 **Creating a PivotTable** — Insert → PivotTable → select source data.
16.2 **Rows / Columns / Values / Filters** — the four zones you drag fields into.
16.3 **Changing the Aggregation** — Value Field Settings → Sum/Count/Average/Max/etc.
16.4 **Filtering & Sorting in a PivotTable** — narrowing down and ordering summarized results.
16.5 **Grouping Data** — grouping dates into Month/Quarter/Year automatically.
16.6 **Refreshing a PivotTable** — manually re-syncing after source data changes (not automatic).
16.7 **PivotCharts** — a chart built directly on top of PivotTable data.

## 17. Chart Types — Choosing the Right One
17.1 **Column & Bar Charts** — category comparisons; bar suits long category names.
17.2 **Line Charts** — tracking trends, especially over time.
17.3 **Area Charts** — cumulative volume changes over time (stacked or standard).
17.4 **Box Plots** — distribution, median, and outlier detection.
17.5 **Scatter Plots** — correlation between two variables, often with trendlines.
17.6 **Waterfall Charts** — financial change tracking: starting value → +/- changes → final value.
17.7 **Treemaps** — hierarchical data where rectangle size reflects value.
17.8 **Sparklines** — tiny in-cell line/column/win-loss charts.
17.9 **Trendlines** — Linear, Exponential, or Polynomial — predicting future direction.
17.10 **Pie & Doughnut Charts** — parts of a whole; doughnut allows multiple data series.
