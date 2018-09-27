---
title: 'Behind the Scenes of the Pivot Table'
description: 'This chapter discuss how a pivot table works, and how it deals with the underlying data.'
---

## How a pivot table works

```yaml
type: VideoExercise
key: h2oz7i0y6n
xp: 50
video_link: //player.vimeo.com/video/154783078
video_hls: //videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8
```

`@projector_key`

1591616a7a00f70ff25263aede6825c5


---

## What does a pivot table do?

```yaml
type: PureMultipleChoiceExercise 
key: 4xacqbd8qz
lang: spreadsheets
xp: 100
```

- Which answer best describes what a pivot table does?

`@possible_answers`

- [It takes a dataset of any size, and allows you to build custom summaries of the data in an easy-to-manage table]
- It converts your original data into a pre-defined format which you cannot adjust
- It subtotals your data only

`@feedbacks`

- Correct!  The pivot table allows you to summarize a large amount of data in just a few seconds!
- There may be an option to select _suggested_ pivot tables, these are only offered for convenience.  You still have full control to customize them.
- Subtotaling is only one of the many options that are available within a pivot table.



---

## Analyze the pivot table

```yaml
type: MultipleChoiceExercise 
key: 0wonloqoq3
lang: spreadsheets
xp: 100
```

- Based on the included Pivot Table which contains rainfall data about 3 cities, which statement is true?

`@possible_answers`

- Seattle, Washington has the highest amount of annual rainfall. 
- The month of April has the most rainfall for each city.
- [Seattle has more rainfall in December, than any other city has in any single month.]

`@feedbacks`

- Compare the totals in rows 14, 27, and 40.
- Each of the cities has several months that are higher than April.
- Correct!  At 154 mm, that is the highest monthly rainfall.



---

## Analyze the pivot table pt 2

```yaml
type: MultipleChoiceExercise 
key: zgpyyoem8g
lang: spreadsheets
xp: 100
```

- Based on the included Pivot Table, What does cell D14 represent?

`@possible_answers`

- There are 10 days of rain in Phoenix, Arizona each year.
- The highest single month of rain in Phoenix had 10 inches of rain.
- [The total annual rainfall in Phoenix is 10 inches. ]

`@feedbacks`

- Look at the header for Column D.  Try again!
- Look at the Row label for row 14; this row contains the annual total.  Try again!
- Correct!  That cell shows the Grand Total of rainfall in inches for Phoenix.



---

## Using filters in a pivot table

```yaml
type: VideoExercise
key: 7c5gomfyzp
xp: 50
```

`@projector_key`

a35f4789428924a91484ed9280a897c1


---

## Selecting filters

```yaml
type: NormalExercise
key: uabqctof6k
lang: spreadsheets
xp: 100
video_link: //player.vimeo.com/video/154783078
video_hls: //videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8
```

Now that you know how to create the body and layout of a pivot table, let's start organizing the data.

One option is to filter the data.  You can do this by selecting a field in the **Filter** section of the pivot table editor.

This will then give you the option to filter based on the contents of that field.

`@instructions`

- Click on the **Add** button in the **Filters** section and select `Month`.
- Once the `Month` box appears, you can then click the dropdown box that appears, and select an individual month.  This time, select January.

`@hint`

- Watch the video again if you can't find it.
- By default, all months will be selected.  So the first thing you'll have to do is click **Clear** in order to remove the current selection.


---

## Filtering by using a string

```yaml
type: NormalExercise
key: bd8di1dee5
lang: spreadsheets
xp: 100
```

Sometimes you will need to select multiple entries within the Filter, which you can do by clicking each selection individually.

However; this can become time-consuming if there are many items to scroll through, such as this example which contains a list of 50 cities.

There is a shortcut to save you some time though, as you can type in a text-string, and select all of the entries that contain that string.  For instance, if you want to select all of the cities in California, you can type "Cali" in the filter, and it will return only those items that contain that string.

`@instructions`

- Click on the **Add** button in the **Filters** section and select `City`.
- Once the `City` box appears, you will need to clear all of the selections, then select only the cities in California.

`@hint`

- Watch the video again if you can't find it.
- Start typing in "California" into the filter field.  After the list narrows down to just those cities, you can select them all.


---

## Filtering on min/max values

```yaml
type: NormalExercise
key: xgwdebhww4
lang: spreadsheets
xp: 100
```

Even though filters are often used to select different groups of items, you can also filter on numerical values as well.  In this example you will select the highest and lowest values in order to determine the extreme outliers of the dataset.

`@instructions`

- In the **Filters** section, select the two highest and two lowest values.

`@hint`

- You will want to clear all of the selections first, then you can select only those values necessary for this exercise.


---

## Filtering on values

```yaml
type: NormalExercise
key: dk38vw755g
lang: spreadsheets
xp: 100
```

Let's try another example.  This time you'll need to find the cities that receive the most days of rainfall in a month.

`@instructions`

- In the **Filters** section, select `Days` and then filter it to only show values of 20 or higher.

`@hint`

- You will want to clear all of the selections first, then you can select only those values necessary for this exercise.


---

## Putting all the pieces together

```yaml
type: VideoExercise
key: ucacgf20ir
xp: 50
video_link: //player.vimeo.com/video/154783078
video_hls: //videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8
```

`@projector_key`

ed5663439e93a1d6206323a4e309adaf


---

## Building a complete pivot table

```yaml
type: NormalExercise
key: co04g6lso2
lang: spreadsheets
xp: 100
```

You have done all of the steps individually, now it's time to put them all together and build a complete Pivot Table from scratch.

Build a pivot table that shows the rainfall by month in each city.

`@instructions`

- In the **Rows** section, select `City` and then select `Month`
- In the **Values** section, select `Millimetres`

`@hint`

- Make sure that the order of the Row labels is correct
- Make sure that no other fields are selected


---

## Building a complete pivot table pt 2

```yaml
type: NormalExercise
key: 6nwfxfrouf
lang: spreadsheets
xp: 100
```

Let's practice some more.

One of the fields in the dataset is the number of days it rained in a given month and city.  Build a pivot table that shows the frequency of each value (number of raindays), and how often each value occurred in each month.

`@instructions`

- In the **Rows** section, select `Days`
- In the **Columns** section, select `Month`
- In the **Values** section, select `City`

`@hint`

- Make sure that the **Rows** and **Columns** are correct
- Make sure that no other fields are selected
- Make sure that the **Values** section shows the *COUNT* of `City`


---

## Building a complete pivot table pt 3

```yaml
type: NormalExercise
key: la9g6gjad9
lang: spreadsheets
xp: 100
```

Let's practice some more.

Build a Pivot Table that shows the number of days and inches of rain for each city.  Create a filter that allows you to filter by month, and filter the table to only show January.

`@instructions`

- In the **Rows** section, select `City`
- In the **Values** section, select `Days` and `Inches`
- In the **Filters** section, select `Month` and then choose January

`@hint`

- Make sure the **Values** section is in the right order
- Make sure that no other **Columns** are selected
- You'll have to clear the selections in the **Filters** field before selecting January