---
title: Workspace basics
description: Describes how to pull basic reports in Workspace
---

# Workspace basics

If you are not familiar with the Workspace tool yet, here are some tips to get you started.

Workspace is Adobe's premier tool to make actionable data-based decisions for your organization. The most common visualization, the freeform table, lets you easily create customized reports using dimensions, metrics, segments, and date ranges.

## Pull a basic ranked report in Workspace

A ranked report shows an aggregated total view of each dimension value, showing the largest values first. These types of reports are useful to see what components of your site are most effective, such as which pages get the most traffic or what products sell the most.

1. Make sure you are logged in to [analytics.adobe.com](https://analytics.adobe.com).
1. In the top navigation bar, click **[!UICONTROL Workspace]**.
1. Click **[!UICONTROL Create New Project]**.
1. In the modal popup, make sure 'Blank Project' is selected, then click **[!UICONTROL Create]**.
1. On the left, you should see a list of dimensions, metrics, segments, and date ranges. Locate the Pages dimension (colored orange), and drag it over to the canvas where it says 'Drop a Dimension Here'.
1. A report showing the top pages for this month can be seen. Analysis Workspace automatically populated the report with the [Occurrences](https://docs.adobe.com/content/help/en/analytics/components/variables/metrics/metrics-occurrences.html) metric.
1. Locate the Visits metric (colored green), and drag it either **over** or **next to** the Occurrences metric header (avoid placing it above the metric). If you drag the Visits metric on top of Occurrences, the metric is replaced in reporting. If you drag the Visits metric next to Occurrences, both metrics are displayed side-by-side.
1. If you'd like to save your project, click **[!UICONTROL Project] > [!UICONTROL Save]** in the upper left menu.

## Pull a basic trended report in Workspace

A trended report shows an over-time view of metrics using the selected date range. These types of reports are useful for identifying trends over time, and can be used to gauge success or failure of business decisions made. For example, you could look at a page views report trended over time to see if a site redesign helped increase or decrease traffic.

1. Make sure you are logged in to [analytics.adobe.com](https://analytics.adobe.com).
1. In the top navigation bar, click **[!UICONTROL Workspace]**.
1. Click **[!UICONTROL Create New Project]**.
1. In the modal popup, make sure 'Blank Project' is selected, then click **[!UICONTROL Create]**.
1. On the left, you should see a list of dimensions, metrics, segments, and date ranges. Locate the Page Views dimension, and drag it to the small space on the canvas labeled **[!UICONTROL Drop a Metric Here]**. Avoid dropping it in the space reserved for dimensions (at least for this exercise).
1. Note that if the report suite has data, you should see a basic page views report trended over the current month. Analysis Workspace automatically brought in the 'Day' date range so you can see the trend of page views for the current month.
1. Locate the Week date range (colored purple) in the list of date range components on the left. Click the date range title to expand and see all date range components, or use the search bar.
1. Drag the Week date range on top of the Day date range header on the canvas to replace it.
1. Note that your trended report is now aggregated by week instead of day.
1. If you'd like to save your project, click **[!UICONTROL Project] > [!UICONTROL Save]** in the upper left menu.

## Experiment with the tool

Since Workspace is a reporting tool, it has no impact on data collection. There are no repercussions to indiscriminately dragging components into a project to see what works. Drag different combinations of dimensions and metrics into your workspace project to see what is available to you.

If you accidentally drag an invalid component to your workspace project or would like to go back a step, press ctrl+Z (Windows) or cmd+Z (Mac) to undo the last action made. You can also start with a clean slate by clicking **[!UICONTROL Project] > [!UICONTROL New]** in the upper left menu.

## Troubleshooting

### When I drag a metric over, it says 'Invalid data'.

Invalid data means that Adobe cannot return data using the combination of dimensions and metrics used in the report. For example, two metrics stacked on top of each other cannot be returned as data, as there is no way to display two metrics that way. Instead, place the metrics side-by-side.

### When I drag a metric over, I don't see any actual data - just zeros.

If you successfully create a workspace report but there's no data, there are a few things you can check:

* Double check the report suite and make sure it's one populated with data.
* If you're using a segment in your report, the segment criteria might not match any data. Try removing the segment or adjusting the segment definition.
* Check the date range in the upper right and make sure it's set to a value that you'd expect.
* Navigate to your website and use the Debugger to validate that data is being collected.

## Additional Resources

Note that the following resources may refer to using Workspace in the traditional Adobe Analytics product, not in Customer Journey Analytics.

* Blog posts:
  * [Empowering Organizations with Smarter Analysis](https://theblog.adobe.com/adobe-analytics-fall-2016-release-empowering-organizations-smarter-analysis/)
  * [Analysis Workspace: The Secret Sauce is Getting Tastier](https://theblog.adobe.com/analysis-workspace-secret-sauce-getting-tastier/)
  * [Why You Should Be Using Analysis Workspace](https://theblog.adobe.com/why-you-should-be-using-analysis-workspace-in-adobe-analytics/)
  * [5 Tips to Maximize Your Productivity with Analysis Workspace](https://theblog.adobe.com/5-tips-maximize-productivity-analysis-workspace/)

## Next steps

There are a lot of directions to go to deepen your understanding of Workspace. Here are some basics that Adobe recommends:

### For end users looking to expand knowledge on how to use Workspace

* [Details on the Workspace UI](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/t-freeform-project.html): Now that you've created a basic report, become more familiar with the rest of the interface.
* [Visualizations in Workspace](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/freeform-analysis-visualizations.html): Freeform tables are merely one type of visualization in Analysis Workspace. Learn how to use other visualizations, such as line charts, bar graphs, and geo maps.
* [Dimensions in Workspace](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/components/dimensions/t-breakdown-fa.html): Learn more about what dimensions are and how to use them in more than just ranked reports.
* [Metrics in Workspace](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/components/apply-create-metrics.html): Learn more about what metrics are and how to use them in other parts of freeform tables.
* [Introduction to segmentation](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/components/t-freeform-project-segment.html): Learn about what segments are and pull a basic report using a segment.
* [Date ranges in Workspace](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/components/calendar-date-ranges/calendar.html): Learn about relative and rolling dates, and use them in workspace projects.
* [Sharing projects](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/curate.html) in Workspace: Show your colleague the awesome Workspace project you created.

### For analysts and admins looking to improve the quality of workspace in their organization

* [Analysis Workspace permissions](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-getting-started.html): Assign users permissions to Workspace via the Adobe Admin Console.
* [Templates in Workspace](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html): Create templates so your colleagues can start with a project space tailored to their needs.
* [Workspace curation](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/curate.html): Create a project that limits available components, making workspace more accessible to those less familiar with the tool
