
# Android Calendar View (Android App)

## Overview
In this tutorial, we’ll be discussing the Calendar Widget using the CalendarView class in our Android Application.

## Android Calendar View
As the name suggests, a Calendar View is used to display and select dates of the Calendar. To add a CalendarView in the XML Layout do the following:
```
<CalendarView
        android:id="@+id/calendarView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"/>
```

## This is how it looks in the Layout Design editor :
Thumbnail:

![1](https://journaldev.nyc3.digitaloceanspaces.com/2018/07/android-calendar-view-xml-design.png)

```
calendarView.setOnDateChangeListener(new CalendarView.OnDateChangeListener() {
            @Override
            public void onSelectedDayChange(@NonNull CalendarView calendarView, int i, int i1, int i2) {
            }
        });
 ```
 
This gets triggered whenever the date is changed by the user.

* i = year
* i1 = month
* i2 = day
In the following section, we’ll create an android application with a custom theme and add a custom range on the CalendarView along with showing the difference between animation and non-animation date changes.


## Project Structure

Thumbnail:

![1](https://journaldev.nyc3.digitaloceanspaces.com/2018/07/android-calendar-view-project-structure.png)

## Output

![2](https://journaldev.nyc3.digitaloceanspaces.com/2018/07/android-calendar-view-output.gif)
