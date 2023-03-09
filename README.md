### An Excel Dashboard for Pakistan’s Development Indicators

![dashboard](https://github.com/saadabidsubhan/pak-growth-indicator-excel/blob/main/Excel-dashboard.jpg)

This project leverages the dynamic functionality of Microsoft Excel to create a dashboard that visualizes relevant metrics in six areas of Pakistan’s economy.

This project was driven by my curiosity about Pakistan’s development progress over the years along with my eagerness to sharpen my skills with Microsoft Excel. I wanted to create a visually appealing dashboard displaying the trend in different development indicators over the years. After searching for reliable data, I found a country-wise Sustainable Development Goals dataset by the WHO.

The first step was to filter out data that was exclusive to Pakistan. The next step was to shape it in such a way that excel was able to recognize it as a table. Since the shape of the data did not allow for the creation of a pivot table, I grouped each metric with its corresponding categories in separate sheets.

After this, I used the LIST, INDEX, and MATCH functions to create dynamic charts for each indicator type before finally linking them to the main dashboard.

To include metrics with missing values in some years, I opted to create a histogram rather than a line chart as the line chart would drop to zero at missing values as opposed to a histogram which would not create a bar for the year with the missing value.

