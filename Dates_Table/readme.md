# About this dates table

### Tell me what's fancy in here?
- Use parameters to set the start and end date of your Dates table
- Use parameters to set the start of your fiscal period
- To make your visuals prettier, months and weekdays are available as "J F M A M...D"
- WEEK functionality (ISO weeks to be specific)
- Fiscal functionality (year, period, week)
- Current (year, quarter, month, week). Default slicers on your page to this so that the current year etc is always selected by default
- Offsets (years, quarters, months, days). Apparently very powerful
- IsAfterToday. Helps with cumulative totals (see example in pbix)

### Where did it originate from?
The *Extended dates table* was originally written up by Melissa and Brian over at the Enterprise DNA forum. See their original thread [here](https://forum.enterprisedna.co/t/extended-date-table-power-query-m-function/6390).
### How does this version differ from their original?
- I changed the naming of some columns on the date table. For instance, I appended all *sorting* columns with "_sort."
- I cleaned up naming in the script (to suit myself)
### Which shall I use, yours or the original?
For a 100% risk free experience, use Melissa's. I've tweaked this table to suit myself. It may or may not have a few glitches. I haven't found any (yet).

### Whats the fastest way to get started?
There is a power bi file (.pbix) in this folder as well as corresponding excel file (containing sample data). Open the pbix report and take a look at the Overview page. 

### But I only want the M-CODE which generated this Dates table, now what?
In this folder, find the file DatesTable_MCODE.txt. Then open up power bi > Transform Data > New Query (Blank) > Advanced Editor > copy and paste the contents of this file in there exactly.

### Why did you put this here? 
To (re-)learn github. To send links to people I know. And having already learnt my lesson, to be able to back track once I completely break the dates table.
