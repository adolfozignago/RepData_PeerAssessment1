---
title: "Reproducible Research: Peer Assessment 1"
output: 
  html_document:
    keep_md: true
---


## Loading and preprocessing the data

...{r }
fileURL = "https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip"
fileDest = "activity.zip"
if(!file.exists(fileDest)) {
        download.file(fileURL, fileDest, method = "curl", mode = "wb")
        activityfile <- unzip(fileDest)
} else {
        activityfile <- unzip(fileDest)
}

actDataSet <- read.csv()
...


## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
