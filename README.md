# Project description
You work as a video analyst *ads* at the advertising agency Sterling & Draper. You spend a lot of time analyzing the videos that are currently trending on YouTube to determine the type of content that will appeal to your marketing team.

Each video has a specific category (Entertainment, Music, News & Politics, etc.), region and trending date.

A video may be in the trending segment for several days in a row.

Every week, two new employees ask you the same question:

- What video categories were *trending* last week?
- How is it distributed in each region?
- What categories are most popular in the United States?

In your sixth week on the job, you decide that it's time to automate this process. You also decide to create a dashboard.

## Summary of technical guidelines:

- Business purpose: analyze the history of videos that are currently *trending* on YouTube
- Frequency of using *dashboard*: at least once a day
- Targeted users *dashboard*: video planning managers *ads*
- Data content *dashboard*:
     - Videos that have *trending*, grouped by day and category
     - Videos that are currently *trending*, grouped by country
     - Table linking categories and countries
- Parameters used to group data:
     - Date and time *trending*
     - Video categories
     - Country
- Data:
     - History *trending*  — absolute values divided by day (two graphs: absolute value and percentage ratio)
     - Sessions, grouped by country — relative value (% sessions)
     - Relationship between categories and countries — absolute values (table)
- Significance: all charts are equally important
- The data source for *dashboard*: *data engineer* will create an aggregate table named `trending_by_time`. Here is the structure:
     - `record_id` — primary key
     - `region` — country/geographical area
     - `trending_date`  — date and time
     - `category_title`  — video category
     - `videos_count`  — the number of videos in the *trending* segment
- The table is stored in *database* `youtube`
- Data update interval: once every 24 hours, at midnight UTC time
- Graphics, *dashboard* controls, and their arrangement:

&ensp;&thinsp;&ensp;&thinsp;&ensp; ![EN_Description](https://github.com/yusufsp7/Data_Analysis_Projects/blob/Project_11_EN/source_files/EN_Description.png)

# Dashboard
This is a dashboard based on the technical guidelines above
![Gif](https://github.com/yusufsp7/Data_Analysis_Projects/blob/Project_11_EN/source_files/Tableau%20Public%20-%20Youtube%20Trending.gif)

Please open this link to see the full version: [Youtube Dashboard](https://public.tableau.com/views/YoutubeTrending_16798306360250/Dashboard1?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)\
Presentation: [Presentation](https://drive.google.com/file/d/1__B1Fu2OKJg0wqmp0Msr7WTlXktX7uew/view?usp=sharing)
