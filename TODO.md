# To do

### Backlog

* May need to chunk queries as struggling to assign object to vetcor of size 1.3MB
* cache % missing for queried dates and decide on threshold to throw warning
* format no records nicely with commas
* Conditional formatting of UI messages, eg invalid Email in red.
* defer to user - ability to specify single dates to test on?
* defer to user - pattern cleansing,   pattern = "souhbound", replacement = "southbound", script 13.
* defer to user - site status - active / inactive context.
* defer to user - splitting of combo output csvs by sitetype or by number of rows.
* Remove all missing report.txt logic or move to logs.
* Remove busy spinner & replace with progress bar, updating pipeline with progress object.
* Persistent Email storage between sessions locally.
* Max-width on table previews required. Table columns spilling into adjacent UI column. Tried css: width: 83% !important; not working, tried with '.middleTable' & '.middleTable table' selectors.
* possible to use conditional logic in selected value of dateRangeInput? eg, if testing,
diplay test date else display today's date.



### Performance

* 2 days (1st to 2nd Sep 2020) takes: Time difference of 5.679 mins, 3.6 times faster using parallel compute.
* Scale up to 1 month, previously took 2.25 hrs for Sep 2020.
* Queried 31 days for all sites in Time difference of 52.702 mins
* 2.6 times faster using parallel compute. Comes at a cost though - requires additional RAM, from 20GB up to 30GB.