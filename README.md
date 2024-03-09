# pandas-challenge

This analysis is done on file of student data showing student test scores from various grade levels and schools. Many calculations were performed on the data in various groups by utilizing pandas dataframes. Test scores were evaluated based on grade level, school, school budget, and student body size to name a few.

From the analysis performed on the data, two conclusions that can be drawn are:

1. On average, the more schools spend per student, the worse their students perform academically. When schools are grouped into four per-student spending ranges as in the spending_summary dataframe, the average math and reading scores as well passing rates are highest for schools spending less than $585 per student. As the next highest spending group is evaluated, the results decrease each time. Additionally it appears that large schools (2,000-5,000 students) have significantly lower passing rates than schools with a smaller student body, as seen in the size_summary dataframe. This suggests that a more intimate learning environment is more conducive to success than a higher budget per student.


2. Students attending Charter schools are more likely to pass than those attending District schools. When displaying the top 5 highest performing schools by overall passing percentage, all of the top 5 schools were Charter schools. Conversely, when displaying the bottom 5 performing schools by overall passing percentage, all 5 of the lowest performing schools fell under the District school type. This suggests that Charter schools are much more effective at educating their students.