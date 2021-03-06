Widgets Types
-------------

There are 14 widget templates in Report Portal:
 
- Launch statistics line chart   
- Launch statistics trend chart 
- Overall statistics panel 
- Launches duration chart 
- Launch execution and issue statistic 
- Project activity panel 
- Test-Cases growth trend chart 
- Investigated percentage of launches 
- Launches table 
- Unique bugs table 
- Most failure test-cases table
- Failed cases trend chart 
- Non-Passed test-cases trend chart 
- Different launches comparison chart 

The description of them is provided below.


### Launch statistics line chart

The widget can be used in two modes - Launch mode and Timeline mode:

- widget in Launch mode shows the growth trend in the number of test cases with each selected statuses from run to run,
- widget in Timeline mode shows sum of test cases with each selected statuses distributed by dates.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on 
the second step:

- Select filter from available in the list or create a new one to define the range of data.
- Items - number of launches, that will be shown on the widget (should be 1-150).  Default meaning is 50.
- Select issue types for displaying. All types are selected by default. To specify them, uncheck unnecessary items in "Criteria for Widget".
- Select mode: Launch or Timeline.

**Widget view**

Widget contains agenda with selected statuses; you can click on a status to remove/add it to the chart.

Widget view in Launch mode:

- X-axis shows launches numbers and launches names (on hover).
- Y-axis shows sum of test cases with each selected statuses.

Tooltip on mouse hover over chart area shows launch details: launch name and number, launch start time and launch statistics.

[ ![Image](Images/userGuide/widgetTypes/launchStatisticsLineChart.png) ](Images/userGuide/widgetTypes/launchStatisticsLineChart.png)


Widget view in Timeline mode:

- X-axis shows dates and weekdays.
- Y-axis shows sum of launches statistics with each selected statuses, distributed by weekdays.

Tooltip on mouse hover over chart area shows details: date and total launches statistics. 

Widget has clickable sections; when you click on specified section in widget, the system forwards you to launch view for appropriate selection.

[ ![Image](Images/userGuide/widgetTypes/launchStatisticsLineChartTimeline.png) ](Images/userGuide/widgetTypes/launchStatisticsLineChartTimeline.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.


### Launch statistics trend chart

The widget can be used in two modes - Launch mode and Timeline mode:

- widget in Launch mode shows the growth trend in the number of test cases with each selected statuses from run to run,
- widget in Timeline mode shows sum of test cases with each selected statuses distributed by dates.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the next step:

- Select filter from available in the list or create a new one to define the range of data.
- Items - number of launches, that will be shown on the widget (should be 1-150). Default meaning is 50.
- Select issue statuses for displaying. All statuses are selected by default. To specify them, uncheck unnecessary items in "Criteria for Widget".
- Select mode: Launch or Timeline.

**Widget view**

Widget contains agenda with selected statuses; you can click on a status to remove/add it to the chart.

Widget view in Launch mode:

- X-axis shows launches numbers and launches names on hover.
- Y-axis shows sum of test cases with each selected statuses.

Tooltip on mouse hover over chart area shows launch details: launch name and number, launch start time and launch statistics. 

[ ![Image](Images/userGuide/widgetTypes/launchStatisticsTrendChart.png) ](Images/userGuide/widgetTypes/launchStatisticsTrendChart.png)

Widget view in Timeline mode:

- X-axis shows dates and weekdays.
- Y-axis shows sum of launches statistics with each selected statuses, distributed by weekdays.

Tooltip on mouse hover over chart area shows details: date and total launches statistics. 

Widget has clickable sections, when you click on specified section in widget, the system forwards you to launch view for appropriate selection.

[ ![Image](Images/userGuide/widgetTypes/launchStatisticsTrendChartTimeline.png) ](Images/userGuide/widgetTypes/launchStatisticsTrendChartTimeline.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.


### Overall statistics panel

Panel shows summary of test cases with each statuses in the selected launches.

**Widget configuration**

To configure the widget, click "Add Widget" button on the dashboard header, select template and specify the following settings on the next step:

- Select filter from available in the list or create a new one to define the range of data.
- Items - number of launches, that will be shown on the widget (should be 1-150). Default meaning is 50.
- Select issue statuses for displaying. All statuses are selected by default. To specify them, uncheck unnecessary items in "Criteria for Widget".

**Widget view**

[ ![Image](Images/userGuide/widgetTypes/overallStatisticsPanel.png) ](Images/userGuide/widgetTypes/overallStatisticsPanel.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.
 

### Launches duration chart

**Widget configuration**

You can specify "Items" - number of launches, that will be shown on the widget.

To do this, click "Add New Widget" button on the dashboard header, select template and specify "Items" (not more than 150 launches) on the next step.

**Widget view**

Widget shows the duration of the filtered launches.

- X-axis shows launches duration.
- Y-axis shows launches numbers and launches names on hover.

Tooltip on mouse hover over chart area shows launch details: launch name, number and duration. 

Widget has clickable sections, when you click on specified section in widget, the system forwards you to launch view for appropriate selection.

[ ![Image](Images/userGuide/widgetTypes/launchesDurationChart.png) ](Images/userGuide/widgetTypes/launchesDurationChart.png)
 
>**Notes:**
Widget doesn't contain IN PROGRESS launches.


### Launch execution and issue statistic

**Widget configuration**

The only one setting that could be selected for the widget is filter.

**Widget view**

Widget shows statistics of the last finished launch in chosen filter. Statistics is divided into 2 sections:

- Skipped, Passed, Failed
- Product Bug, System Issue, Automation Bug, No Defect (default and custom) and To Investigate.

Widget contains agenda with statuses, the user can click on a status to remove/add it to the chart.

Tooltip on mouse hover over chart area shows launch details: launch name, number and duration. 

Statistics for every type is shown in percentage. On hover the exact number is shown for the curtain type.

Widget has clickable sections, when you click on specified section in widget, the system forwards you to launch view for appropriate selection.

[ ![Image](Images/userGuide/widgetTypes/launchExecutionAndIssueStatistic.png) ](Images/userGuide/widgetTypes/launchExecutionAndIssueStatistic.png)


### Project activity panel

Widget shows all activities occurring on the project.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the second step:

- Actions for Widget - actions, that will be present. The following actions are available: Update Project Settings, Update Defect Types, Delete Launch, Start Launch, Finish Launch, Share Widget, Dashboard, Unshare Widget, Dashboard, Post Issue to BTS, Add, Register User, Update BTS. By default all actions are checked.

- Items - number of actions, that will be shown on the widget (should be 1-150). Default meaning is 50.

- Project members. In case of empty field actions of all project members will be shown.

**Widget view**

Actions on the widget are present in a table, separated by days. Action messages have the following format:

>   *Member (name) did action.*  
>   *Time - displayed in 'time ago' format (i.e. "10 minutes ago"). On mouse hover, the system should display accurate action time.)*

[ ![Image](Images/userGuide/widgetTypes/projectActivityPanel.png) ](Images/userGuide/widgetTypes/projectActivityPanel.png)


### Test-Cases Growth trend chart

The widget can be used in two modes - Launch mode and Timeline mode:

- widget in Launch mode shows the increment of test-cases from run to run,
- widget in Timeline mode shows the increment of test-cases distributed by dates (in launches with the largest number of test-cases per day).

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the next step:

- Select filter from available in the list or create a new one to define the range of data.
- Items - number of launches, that will be shown on the widget (should be 1-150). Default meaning is 50.
- Select mode: Launch or Timeline.

**Widget view**

Widget view in Launch mode:

- X-axis shows launches numbers and launches names on hover.
- Y-axis shows the increment of test-cases.

Tooltip on mouse hover over chart area shows launch details: launch name and number, launch start time and launch statistics - total number of test cases and test cases growth.

[ ![Image](Images/userGuide/widgetTypes/testCasesGrowthTrendChart.png) ](Images/userGuide/widgetTypes/testCasesGrowthTrendChart.png)

Widget view in Timeline mode:

- X-axis shows dates and weekdays.
- Y-axis shows the increment of test-cases in launches with the largest number of test-cases per day.

Tooltip on mouse hover over chart area shows launch details: date and launch statistics - total number of test cases and test cases growth.

Widget has clickable sections, when you click on specific section in widget, the system forwards you to launch view for appropriate selection.

[ ![Image](Images/userGuide/widgetTypes/testCasesGrowthTrendChartTimeline.png) ](Images/userGuide/widgetTypes/testCasesGrowthTrendChartTimeline.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.


### Investigated percentage of launches

The widget can be used in two modes - Launch mode and Timeline mode:

- widget in Launch mode shows percentage of "Investigated" and "To Investigate" items by launch to sum of (Product Bugs + Auto Bugs + System Issues + To Investigates).
- widget in Timeline mode shows percentage of "Investigated" and "To Investigate" items to sum of (Product Bugs + Auto Bugs + System Issues + To Investigates) in all runs per day, distributed by dates.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and and specify the following settings on the next step:

- Select filter from available in the list or create a new one to define the range of data.
- Items - number of launches, that will be shown on the widget (should be 1-150). Default meaning is 50.
- Select mode: Launch or Timeline.

**Widget view**

Widget contains agenda with "To Investigate" and "Investigated" labels.

Widget view in Launch mode:

- X-axis shows launches numbers and launches names on hover.
- Y-axis shows percent of "Investigated" and "To Investigate" items to sum of (Product Bugs + Auto Bugs + System Issues + To Investigates).

Tooltip on mouse hover over chart area shows launch details: launch name and number, launch start time and percentage of "Investigated" or "To Investigate" items.

[ ![Image](Images/userGuide/widgetTypes/investigatedPercentageOfLaunches.png) ](Images/userGuide/widgetTypes/investigatedPercentageOfLaunches.png)

Widget view in Timeline mode:

- X-axis shows dates and weekdays.
- Y-axis shows percent of "Investigated" and "To Investigate" items to sum of (Product Bugs + Auto Bugs + System Issues + No Defects + To Investigates), distributed by dates.

Tooltip on mouse hover over chart area shows launch details: date and percentage of "Investigated" or "To Investigate" items.

Widget has clickable sections, when you click on specific section in widget, the system forwards you to launch view for appropriate selection.

[ ![Image](Images/userGuide/widgetTypes/investigatedPercentageOfLaunchesTimeline.png) ](Images/userGuide/widgetTypes/investigatedPercentageOfLaunchesTimeline.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.


### Launches table

Widget shows the configurable table of launches.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the second step:

 - Select criteria for widget: Total, Passed, Failed, Skipped, Product Bug, Automation Bug, System Issue, To Investigate, Tags, User, Description, Start time, Finish time. All criteria are selected by default. To specify them, uncheck unnecessary items in "Criteria for Widget".
 - Items -  number of launches, that will be shown on the widget (not more then 150). Default meaning is 50.

**Widget view**

Widget has a table view.

Widget has clickable elements (launch name, owner, tags, number of items); when you click on specific element in widget, the system forwards you to launch view for appropriate selection.

[ ![Image](Images/userGuide/widgetTypes/launchesTable.png) ](Images/userGuide/widgetTypes/launchesTable.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.


### Unique bugs table

Widget shows real identified bugs, posted to the Bug Tracking System from Report Portal, and existing bugs, that were added to the items on Report Portal.

**Widget configuration**

To configure widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the second step:

  - Select filter from available in the list or create a new one to define the range of data.
  - Items - number of launches, that will be used to collect bugs (should be 1-150). Default meaning is 10

**Widget view**

Widget has a table view, found bugs are sorted by the date they were posted or added.

Widget has the following data displayed:

- Bug ID  -  link to the issue in Bug Tracking System.
- Found in - link to the test item, to which the bug was posted/added.
- Submit date  - date the bug was submitted/added. Time is displayed in 'time ago' format (i.e. "10 minutes ago"). On mouse hover the system should display accurate action time.
- Submitter  - user, who submitted/added the bug.

[ ![Image](Images/userGuide/widgetTypes/uniqueBugsTable.png) ](Images/userGuide/widgetTypes/uniqueBugsTable.png)

>**Notes:**
Bugs from launches IN PROGRESS are not shown on the widget.
In case the bug is provided for the few items, all of items will be listed in "Found in" column.


### Most failure test-cases table

Widget contains table with statistical information about TOP-20 most problematic tests cases.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the second step:

 - Criteria for Widget - Failed, Skipped, Product Bug, Automation Bug, System Issue, No Defect. Failed is selected by default.

 - Launches count - number of launches for selection (should have size 2-150). By default, "Launches count" is 30.

 - Launch name (required option).

**Widget view**

Widget has a table view with the following data is displayed:

- Test Item name
- Find in last launch - link to the Step level of the last launch
- Failed - count of found failed results
- Last failure - date and time of last run, when the test item was failed, displayed in 'time ago' format (i.e. "10 minutes ago"). On mouse hover the system will display accurate start time.

[ ![Image](Images/userGuide/widgetTypes/mostFailureTestCasesTable.png) ](Images/userGuide/widgetTypes/mostFailureTestCasesTable.png)

>**Note:**
Widget contains statistic of most problematic tests cases in all launches, except IN PROGRESS and INTERRUPTED launches.


### Failed cases trend chart

Widget shows the trend of growth in the number of failed test cases (Product Bugs + Auto Bugs + System Issues + No Defects + To Investigates) from run to run.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the second step:

 - Select filter from available in the list or create a new one to define the range of data.
 - Items - number of launches, that will be shown on the widget (not more then 150). Default meaning is 50.

**Widget view**

Widget contains agenda: "Failed".

- X-axis shows launches numbers and launches names on hover.
- Y-axis shows number of Failed issues (sum of Product Bugs + Auto Bugs + System Issues + No Defects + To Investigates).

Tooltip on mouse hover over chart area shows launch details: launch name and number, launch start time and number of failed cases.

[ ![Image](Images/userGuide/widgetTypes/failedCasesTrendChart.png) ](Images/userGuide/widgetTypes/failedCasesTrendChart.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.


### Non-Passed test-cases trend chart

Widget shows the percent ratio of non-passed test cases (Failed + Skipped) to "Total" cases from run to run.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the second step:

- Select filter from available in the list or create a new one to define the range of data.
- Items - number of launches, that will be shown on the widget (not more then 150). Default meaning is 50
 
**Widget view**

Widget contains agenda: % (Failed + Skipped) / Total.

- X-axis shows launches numbers and launches names on hover.
- Y-axis shows percent of sum Failed + Skipped test cases to Total.

Tooltip on mouse hover over chart area shows launch details: launch name and number, launch start time and percentage of non-passed cases.

[ ![Image](Images/userGuide/widgetTypes/nonPassedTestCasesTrendChart.png) ](Images/userGuide/widgetTypes/nonPassedTestCasesTrendChart.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.


### Different launches comparison chart

Widget allows to compare statistics for 2 last launches side by side.

**Widget view**

- X-axis shows launches numbers and launches names on hover.
- Y-axis shows percentage of test-cases by statuses.

**Widget configuration**

To configure the widget, click "Add New Widget" button on the dashboard header, select template and specify the following settings on the second step:

- Select filter from available in the list or create a new one to define the range of data.

**Widget view**

Widget contains agenda with statuses, the user can click on a status to remove/add it to the chart.

Tooltip on mouse hover over chart area shows launch details: launch name and number, launch start time and percentage of test cases of particular type.

Widget has clickable sections, when you click on specific section in widget, the system forwards you to launch view for appropriate selection.

[ ![Image](Images/userGuide/widgetTypes/differentLaunchesComparisonChart.png) ](Images/userGuide/widgetTypes/differentLaunchesComparisonChart.png)

>**Notes:**
Widget doesn't contain IN PROGRESS launches.