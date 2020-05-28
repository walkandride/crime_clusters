## Introduction

This is an attempt to perform cluster analysis on the [Virginia Beach police incident crime file](https://data.vbgov.com/Public-Safety/Police-Incident-Reports/iqkq-gr5p).

In my initial attempts, I ran into problems processing the entire dataset.  Trying to process the dataset resulted in slow performance and insufficient memory errors.  My i5-2540M 16GB Windows 10 Pro laptop and my coding implementation were not up to the task.  

I revised how I processed the data.  Breaking up the dataset by year, resulted in similar problems if there were a large number of data points.  Further filtering by year and quarter solved my issues.

