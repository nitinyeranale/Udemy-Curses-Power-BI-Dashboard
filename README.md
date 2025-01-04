# Udemy Online Education Courses Data Analysis (Interactive Dashboard creation using Microsoft Power BI)
## Project Objective
This Power BI report aims to analyze Udemy's online course offerings. Key insights will focus on the popularity of courses, pricing patterns, review trends, content duration, and subject categories. This report aims to help stakeholders identify popular courses, understand pricing trends, and gain insights into user preferences across different subjects and levels.

## Dataset Information
The dataset contains information on Udemy's online courses, including unique identifiers, course details, pricing, popularity, difficulty levels, and publication dates
## Dataset Columns
1. course_id: A unique identifier for each course.
2. course_title: The title of each course as it appears on Udemy.
3. url: A URL linking to the course's Udemy page.
4. is_paid: Indicates whether the course is paid or free.
5. price: The course price is in USD (for paid courses only).
6. num_subscribers: The number of users enrolled in the course.
7. num_reviews: The number of reviews the course has received.
8. num_lectures: The total number of lectures in the course.
9. level: The course's difficulty level (e.g., All Levels, Intermediate Level).
10. content_duration: Total duration of the course in hours.
11. published_timestamp: The date and time of the course's publication.
12. subject: The main category of the course (e.g., Business Finance, Web Development).

## Dataset Link 
- <a href="https://github.com/nitinyeranale/Udemy-Curses-Power-BI-Dashboard/blob/main/udemy_courses_dataset.csv">Dataset</a>

## Data Preparation and Transformation
1. Loading Data:
                 - Imported the Udemy dataset into Power BI for transformation and analysis.
3. Data Cleaning:
                  - Verified the accuracy of URLs and ensured that all columns were populated.
                  - Removed any duplicate entries to ensure accurate analysis.
4. Data Transformation:
                       - Published Date: Extracted month and year for time-based analysis of course publishing trends.
                       - Price Adjustment: Converted price to numerical data for courses marked as paid, replacing null values with zero for free courses.
                       - Categorization: Classified courses into "Free" and "Paid" based on the is_paid column.

## Key Metrics and Measures
1. Total Courses: Count of all unique course_id entries.
2. Total Subscribers: Sum of num_subscribers to show the total enrolled students.
3. Average Price: Calculated average price for paid courses.
4. Total Reviews: Sum of num_reviews.
5. Content Duration: Sum of content_duration for total hours of content available.
6. Average Lectures: Average number of lectures per course.
7. Popular Subjects: Total count and percentage of courses by subject.

## Visualizations
1. Total Courses by Subject:
                           - Bar chart displaying the number of courses available per subject.
3. Subscribers by Subject:
                           - A bar or column chart showing the total number of subscribers per subject area.
5. Revenue Insights:
                      - Average Price per Subject: Matrix showing average prices for paid courses by subject.
                      - Revenue Generation by Subject: Calculated revenue by multiplying price with num_subscribers for each course.
7. Reviews Analysis:
                     - Average Reviews per Course Level: Stacked bar chart with the average number of reviews segmented by difficulty level.
                     - Reviews and Popularity Trend: Line chart showing monthly trend in number of reviews and new course publications.
9. Content Duration Analysis:
                            - Total Duration per Subject: A pie chart or donut chart displaying the distribution of total content hours by subject.
11. Free vs. Paid Courses:
                          - A clustered bar chart comparing the number of free and paid courses across all subjects.
13. Time-Based Insights:
                        - Course Publishing Trend: Line chart showing the number of courses published over time.

## Dashboard Interaction : 
- <a href="https://github.com/nitinyeranale/Udemy-Curses-Power-BI-Dashboard/blob/main/Dashboard_1.png">Dashboar1</a>
- <a href="https://github.com/nitinyeranale/Udemy-Curses-Power-BI-Dashboard/blob/main/Dashboard_2.png">Dashboar2</a>
- <a href="https://github.com/nitinyeranale/Udemy-Curses-Power-BI-Dashboard/blob/main/Dashboard_3.png">Dashboar3</a>

## Report Insights and Analysis
1. Popular Course Subjects: Identification of the most popular subject categories based on total subscribers.
2. Pricing Analysis: Insights into average course prices across different subjects and course levels.
3. Content Duration Trends: Analysis of how content length varies by subject and level.
4. Free vs. Paid Course Preferences: Analysis of user preferences between free and paid courses.
5. Subscriber and Review Trends: Evaluation of trends in course subscriptions and reviews, helping to identify highly engaging subjects or instructors.

## Future Enhancements
1. Course Completion Rate: Incorporate data on completion rates if available to gauge user engagement.
2. Instructor-Level Analysis: Add instructor data to analyze performance at the instructor level.
3. Advanced Price Analysis: Incorporate dynamic pricing changes over time to understand pricing trends.
4. Regional Insights: If location-based data is available, add insights based on geographic trends.
