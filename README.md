[This data is published under an [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license](https://creativecommons.org/licenses/by-nc-sa/4.0/)]

# About this story

**[How the nation’s growing racial diversity is changing our schools](https://www.washingtonpost.com/graphics/2019/local/school-diversity-data/)**

More students attend schools with children of different races than ever before, but segregation persists in urban districts.

# About the folders in this repo

* **[output_data](https://github.com/WPMedia/student_integration_analysis/tree/master/output%20data)** - Output data file that includes the following for school districts during the 1994-1995 and 2016-2017 school years:
    - leaid: unique school district identifier
    - lea_name: school district name
    - st: state of school district
    - school_year: school year
    - aian, asian, black, hispanic, white, multi: proportion of student population for each race
    - total: number of students
    - diverse: the level of diversity, defined as "Diverse", "Undiverse" and "Extremely undiverse"
    - variance: the variance ratio
    - int_group: the level of integration, defined as "Highly integated", "Somewhat integrated" and "Not integrated"

* **[analysis](https://github.com/WPMedia/student_integration_analysis/tree/master/analysis)** - R Markdown file that generates summary tables and output file 

# Source data

This data predominantly relies on the [Common Core of Data](https://nces.ed.gov/ccd/ccddata.asp) from the National Center for Education Statistics. Links to the underlying data are provided in the R Markdown file.


Additional details for this analysis can be found in the [methdology section](https://www.washingtonpost.com/graphics/2019/local/school-diversity-data/#methodology) of the story. 

# Guidelines for using data

If you publish an online story, graphic, map or other piece of journalism based on this data set, please credit The Washington Post, link to the [original source](https://www.washingtonpost.com/graphics/2019/local/school-diversity-data/), and [send us an email](mailto:maria.sanchezdiez@washpost.com) when you’ve hit publish. We want to learn what you discover and will attempt to link to your work as part of cataloguing the impact of this project.
