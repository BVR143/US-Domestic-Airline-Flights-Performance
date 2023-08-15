# `US-Domestic-Airline-Flights-Performance`
## `Objective` :
As Data Analyst , We are given a task to monitor and report the US Domestics Airline Flights Performance . The main goal of this Project is to Analyze the performance of reporting Airline to improve the flight reliability thereby imporoving customers reliability

Below are the key reporting Items :
* Yearly Airline Performance Repprt
* Yearly Average Flight Delay Statistics

## `Components of the Dashboard Report`
### 1. Yearly Airline Performance Repprt
* Number of Flights under different cancellation cateogory using `Bar Chart`
* Average flights time by reporting airline using `Line chart`
* Percentage of diverted airport landings per reprting airline using `Pie chart`
* Number of flights flying from each state using `Choropleth Map`
* Number of flights flying to each state from a reporting airline using `treemap chart`
### 2. Yearly Average Flight Delay Statistics
* Monthly average `Carrier delay` by reporting airline for the givven year
* Monthly average `Weather delay` by reporting airline for the givven year
* Monthly average `Ntional Air System delay` by reporting airline for the given year.
* Monthly average `Security delay` by reporting airline for the given year.
* Monthly average `Late Aircraft delay` by reporting airline for the given year.
## `What I had Done`
## Task 1 : Imported Packages
* `Pandas`
* `dash`
* `plotly`
* `plotly_html_components as html`
* `plotly_core_components as dcc`
* `dash.dependencies`
## Task 2 : Added Title to the Dashboard
* Provided the title of the application as `US Domestic Airline Flights Performance` using `html.H1()`
* Made the heading center aligned, set color as `#503D36`, and font size as `24`.
## Task 3 : Added the Dropdown menu
* Created two dropdown menues for selceting the report type and year using `dcc.Dropdown()`
* Set `id` as `input-type` to be a parameter.
* Set options to list containing dictionaries with key as label and user provided value for labels in value.

1st dictionary

label: Yearly Airline Performance Report
value: OPT1
2nd dictionary

label: Yearly Airline Delay Report
value: OPT2
Set placeholder to Select a report type.

Set width as 80%, padding as 3px, font size as 20px, text-align-last as center inside style parameter dictionary.
