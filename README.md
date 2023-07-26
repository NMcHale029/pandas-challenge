# pandas-challenge

### Dependencies
This notebook uses Pandas and Pathlib

### Report Overview
Report includes summary data for the district and schools. Highest and lowest performing schools are called out. Math and Reading scores and passing rates are reported by school, by grade by school, by spending per student, school size, and by school type. Further analysis is provided on the relationship between school size and funding by school type.


### Analysis
- The District and School Summaries provide an overview of all math and reading scores, budgets, size and types of schools in the district.
- A summary of the highest and lowest preforming schools are also provided. An observation that stands out in these two charts is that all of the top 5 performaing schools are Charter schools, and all of the 5 lowest performing schools are District schools. This is reenforced when comparing performance by school type.
- When we look at scores across grades, there is no noticable difference between grades at any individual school. With the assumption that each grade is covering different content, it might appear that the school a child attends does not impact their score from year-to-year. However, since this data is not longitudinal, this is only a hypothesis, and would need to be further explored.
- Math and Reading scores and passing rates seem to be negatively correlated with funding and size. The difference in size appears between medium and large schools, while small and medium sized schools perform about the same.
- I created an additional chart to show how School Type compared with School Size and Budget per Student. Since size and budget had a noticable correlation to performance it was worth further exploration. It would appear that School Type could be used as a proxy for both size and budgt per student since they have lower funding and are smaller on average. This could mean that the most important factor in student success is which type of school (District or Charter) they attend.
- Further areas of exploration could be into the longitudinal success of different types of schools, and how funding is allocated to Charter Schools. Assuming students self-select into Charter Schools, the students who attend these schools could already be the highest performing students. Also, if the budget data provided is just what the disctrict is contributing, and not the total budget, the data would be skewed if Charter Schools are getting other forms of funding (i.e. Tuition).
