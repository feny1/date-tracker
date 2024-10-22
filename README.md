# Date Tracker 🚀

1. [Overview](#overview)
2. [Usage](#usage)
   - [Setting Dates](#setting-dates)
   - [Selecting Result Format](#selecting-result-format)
   - [Calculating Time Remaining](#calculating-time-remaining)
3. [URL Query Parameters](#url-query-parameters)
   - [Example Usage](#example-usage)
4. [Author](#author)
5. [Social Links](#social-links)

---

## Overview
The Date Tracker is a web application that allows users to calculate the time difference between two dates. Users can set a start and end date, choose a format for the result, and view the time remaining until the end date.

<p align="center">
<img src="https://github.com/feny1/date-tracker/blob/main/screenshot.png?raw=true" width="300" height="500" border="10"/>
</p>

## Usage

### Setting Dates 📅
Users can set the start and end dates using the date input fields. There are also buttons to quickly set the default dates or today's date:
- **Set Default Start Date**: Resets the start date to August 18, 2024.
- **Set Today as Start Date**: Sets the start date to the current date.
- **Set Default End Date**: Resets the end date to November 17, 2024.
- **Set Today as End Date**: Sets the end date to the current date.

### Selecting Result Format 🔍
Users can choose how they want the difference between the two dates to be displayed using the dropdown menu. The options include:
- 🗓️ Weeks
- 📆 Months
- 📅 Years
- ⏳ Days
- 🔄 Days/Weeks
- 📊 Days/Months
- 📈 Days/Years
- 📊 Days/Months/Years

### Calculating Time Remaining ⏰
The application continuously updates to show how much time remains until the end date. If the end date has passed, it will display "Time is up!"

## URL Query Parameters 🌐
The Date Tracker supports the following URL query parameters for pre-setting the start and end dates, as well as the result format:

Where:
- `start`: The start date in `YYYY-MM-DD` format.
- `end`: The end date in `YYYY-MM-DD` format.
- `format`: The desired result format (`weeks`, `months`, `years`, `days`, `daysWeeks`, `daysMonths`, `daysYears`, `daysMonthsYears`).

### Example Usage 💡
To set the start date as January 1, 2024, the end date as December 31, 2024, and display the result in months, your URL would look like this:
```
https://eny.sa/tools/date-tracker?start=2024-01-01&end=2024-12-31&format=months
```
To set the start date as January 3, 2020, and display the result in days / months / years, your URL would look like this:
```
https://eny.sa/tools/date-tracker?start=2020-01-03&format=daysMonthsYears
```
## Author ✍️

**Ehab Yar**

## Social Links 🌍
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ehab-yar-4a1bb4193/)
- [![](https://img.shields.io/badge/X-%23181717.svg?&style=for-the-badge&logo=x&logoColor=white)](https://x.com/_f_eny)
- [![Instagram](https://img.shields.io/badge/Instagram-%23E1306C.svg?&style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/_f_eny)
- [![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?&style=for-the-badge&logo=github&logoColor=white)](https://github.com/feny1)
- [![Website](https://img.shields.io/badge/Website-%23FF5722.svg?&style=for-the-badge)](https://eny.sa)
