# Power BI Dashboard Documentation

## [1. Introduction](#introduction)
Power BI slicers play a crucial role in interactive data analysis and visualization. Slicers act as filters that allow users to refine the data displayed in the dashboard by selecting specific criteria. They enable users to focus on particular subsets of data, providing a more detailed and customized view. Slicers can be created easily in Power BI and offer a user-friendly interface for filtering data. Additionally, I have implemented tooltips in the dashboard, which provide additional information when hovering over visuals. The dashboard features beautiful formatting of all charts and visuals, including color combinations, size, font type, background settings, and many more formatting tools.

## [2. Dashboard Formation](#dashboard-formation)

### [2.1 Loading the Dataset](#loading-the-dataset)
To start, load the dataset in Excel format into Power BI. Create a new dashboard on the blank canvas area and choose a background based on your preference, either from the database or imported from online sources. Transform the price field into a currency format, such as rupees or dollars. In this case, the price has been converted to dollars.

### [2.2 Creating and Formatting Slicers](#creating-and-formatting-slicers)
Create slicers for various fields such as months, quarters (Q1, Q2, Q3, Q4), regions (Midwest, Northeast, South, Southeast, West), retailers (Bevco, DreamCo, FizzySip, Sodapop), and beverage brands (Coca-Cola, Pepsi, Sprite, etc.). After creating slicers, format them using the format options available, such as adjusting the color, width, and other settings. To streamline customization and enhance processing speed, use the format painter tool to replicate formatting across multiple slicers.

Next, create visuals. Use a card visual to display a single field, and then format the callout values with options like bold, italic, underline, font style, and color. Also, edit the category label of the card visual. Plot various charts and plots such as bar plots, pie charts, donut charts, stacked bar charts, and treemaps. For the treemap, apply one of the three types of filtering (basic, advanced, or top N). In this instance, top N filtering has been applied.

### [2.3 Implementing Tooltips](#implementing-tooltips)
To add tooltips to the dashboard, create a new page and select a visual (e.g., a pie chart). In the legend, include the beverage brand, and in the values, include the sum of operating profit. Format the pie chart, disable the background, and apply additional formatting settings as needed.

By implementing these steps, when you hover your cursor over a table, visual, or chart in the main dashboard, you will see the new sheet pie chart displayed along with the main dashboard.

## [3. Conclusion](#conclusion)
This Power BI dashboard demonstrates the effective use of slicers, tooltips, and various formatting techniques to create an interactive and visually appealing data visualization tool. Slicers provide dynamic filtering capabilities, allowing users to explore specific data subsets. The inclusion of tooltips enhances the user experience by providing additional context and information upon hovering. The careful attention to formatting ensures that the dashboard is not only functional but also aesthetically pleasing. By following these steps, you can create a comprehensive and engaging Power BI dashboard that effectively communicates your data insights.

---

<a name="introduction"></a>
## 1. Introduction
Power BI slicers play a crucial role in interactive data analysis and visualization. Slicers act as filters that allow users to refine the data displayed in the dashboard by selecting specific criteria. They enable users to focus on particular subsets of data, providing a more detailed and customized view. Slicers can be created easily in Power BI and offer a user-friendly interface for filtering data. Additionally, I have implemented tooltips in the dashboard, which provide additional information when hovering over visuals. The dashboard features beautiful formatting of all charts and visuals, including color combinations, size, font type, background settings, and many more formatting tools.

<a name="dashboard-formation"></a>
## 2. Dashboard Formation

<a name="loading-the-dataset"></a>
### 2.1 Loading the Dataset
To start, load the dataset in Excel format into Power BI. Create a new dashboard on the blank canvas area and choose a background based on your preference, either from the database or imported from online sources. Transform the price field into a currency format, such as rupees or dollars. In this case, the price has been converted to dollars.

<a name="creating-and-formatting-slicers"></a>
### 2.2 Creating and Formatting Slicers
Create slicers for various fields such as months, quarters (Q1, Q2, Q3, Q4), regions (Midwest, Northeast, South, Southeast, West), retailers (Bevco, DreamCo, FizzySip, Sodapop), and beverage brands (Coca-Cola, Pepsi, Sprite, etc.). After creating slicers, format them using the format options available, such as adjusting the color, width, and other settings. To streamline customization and enhance processing speed, use the format painter tool to replicate formatting across multiple slicers.

Next, create visuals. Use a card visual to display a single field, and then format the callout values with options like bold, italic, underline, font style, and color. Also, edit the category label of the card visual. Plot various charts and plots such as bar plots, pie charts, donut charts, stacked bar charts, and treemaps. For the treemap, apply one of the three types of filtering (basic, advanced, or top N). In this instance, top N filtering has been applied.

<a name="implementing-tooltips"></a>
### 2.3 Implementing Tooltips
To add tooltips to the dashboard, create a new page and select a visual (e.g., a pie chart). In the legend, include the beverage brand, and in the values, include the sum of operating profit. Format the pie chart, disable the background, and apply additional formatting settings as needed.

By implementing these steps, when you hover your cursor over a table, visual, or chart in the main dashboard, you will see the new sheet pie chart displayed along with the main dashboard.

<a name="conclusion"></a>
## 3. Conclusion
This Power BI dashboard demonstrates the effective use of slicers, tooltips, and various formatting techniques to create an interactive and visually appealing data visualization tool. Slicers provide dynamic filtering capabilities, allowing users to explore specific data subsets. The inclusion of tooltips enhances the user experience by providing additional context and information upon hovering. The careful attention to formatting ensures that the dashboard is not only functional but also aesthetically pleasing. By following these steps, you can create a comprehensive and engaging Power BI dashboard that effectively communicates your data insights.
