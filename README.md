# -School_District_Analysis-
Python/Pandas


                                                                         School District Analysis

  Overview of the School District Analysis: 
	The purpose of this analysis was to investigate possible academic dishonesty amongst the 9th grade cohort of Thomas High School. This investigation required the completion of (Aims 1-5): 1) determine the top and bottom performing schools in the district based on the overall passing rate. 2) Determine the average math and reading scores received by students in each grade level at each school. 3) measure school performance based on budget per student, 4) school size, and 5) school type. Aims 1 – 5 were accomplished using the programming language Python to write algorithms, and a Pandas library to manipulate and analyze the data. Pandas was used along with a Jupyter notebook to read the raw data, clean, and inspect the data, merge data sets and perform calculations to deliver in table format a snapshot, and an overview of key metrics regarding the school district and each individual school. 
  
  Results:
1.	After the math and reading scores for the 9th grade cohort from Thomas High School were converted to null values:
  a.	The district summary showed changes in:
    i.	% Passing Math – from 75% to 74.8%
    ii.	% Passing Reading – from 86% to 85.7%
    iii.	% Overall Passing – 65.1% to 64.9% 
  b.	 The Thomas High school summary showed changes in:
    i.	% Passing Math – from 66.9% to 93.2%
    ii.	% Passing Reading – from 69.7% to 97.0%
    iii.	% Overall Passing – from 65.1% to 90.6%
2.	After removing math and reading scores for the 9th grade cohort at Thomas High School:
  a.	Thomas High School is no longer #2 school or apart of the top 5 schools in the district for overall passing scores.
  b.	9th grade Math and reading scores are null and valued at NaN.
3.	School’s spending <$584 per student have the highest % Overall Passing rate at 90.4% 
4.	Schools spending between $645 – 675 per student have the lowest % Overall Passing rate at 53.5%
5.	Small schools with < 1000 students perform at a % Overall Passing rate of 89.8%
a.	Large schools with 2000 – 5000 students perform at a % Overall Passing rate of 58.3%
6.	Charter schools perform at a % Overall Passing rate of 87.2% 
7.	District schools perform at a % Overall Passing rate of 54.7%


  Summary:
	The school district analysis provided a detailed description of how the removal of the reading and math grades for Thomas High School’s ninth grade cohort affected the overall analysis. The initial analysis scored Thomas High School as the number two school in the district, and after the second analysis Thomas High School was no longer a top five schools. The percent overall passing rate has increased from 65% to 90%, this is due to the decrease in sample size in the second analysis. The school district analysis highlights major factors that may provide reasoning to the success of certain schools. Schools that spend less than $584 per student had a % overall passing rate of 90.4% while schools with the lowest % overall passing rate at 53.5% spend between $645 - $675 per student. Schools with less than 1000 students in their cohort have shown a % overall passing rate of 89.8% while schools with a student population of between 2000 – 5000 show a % overall passing rate of 58.3%. The data shows a strong connection between student population and overall passing rate.
