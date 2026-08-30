HR Attendance Analytics Dashboard

A Power BI project to analyze employee attendance data for April, May and June 2022.

Project Overview

The goal of this project is to convert raw attendance data into a simple and interactive dashboard that shows:

* Total employees
* Attendance and presence percentage
* Work from home (WFH)
* Leave and sick leave
* Daily and monthly attendance trends
* Employees with lower presence percentage

Data Preparation

The data was prepared using Power Query.

Main steps:

* Cleaned the monthly attendance sheets
* Removed unnecessary columns
* Unpivoted the attendance data
* Combined April, May and June data into one table
* Created an attendance status lookup table

Dashboard

The dashboard includes:

* KPI cards for important attendance metrics
* Monthly presence trend
* Daily attendance trend
* Daily WFH trend
* Attendance status distribution
* Bottom 10 employees by presence percentage
* Employee, Date and Status slicers

DAX Measures

Some of the main measures created are:

* Total Attendance Records
* Total Employees
* Present Days
* WFH Days
* Working Days
* Attendance Days
* Presence %
* WFH %
* Leave Days
* Leave %

Half-day attendance and leave statuses were given a **0.5 weight** where applicable.

Tools Used

* Power BI
* Power Query
* DAX
* Excel

Dataset

The dataset was obtained from a YouTube tutorial and is used for learning and portfolio purposes. The original Excel dataset is not included in this repository.
