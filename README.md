Overview
Every year, American high school students take the SAT, a standardized test designed to measure literacy, numeracy, and writing skills. The test consists of three sections - reading, math, and writing, each with a maximum score of 800 points. These scores play a crucial role in college admissions and thus hold significant importance for students and educational institutions.

Analyzing the SAT performance of schools is essential for various stakeholders, including policymakers, educators, researchers, government officials, and parents considering school options for their children.

This project analyzes the SAT performance of NYC high schools using a dataset named schools.csv. We aim to answer three main questions:

Which NYC schools have the best math results?
What are the top 10 performing schools based on the combined SAT scores?
Which single borough has the largest standard deviation in the combined SAT score?
Data
The dataset schools.csv contains information about NYC high schools, including their average SAT scores in math, reading, and writing.

Questions and Analysis
1. Which NYC schools have the best math results?
We define the best math results as an average math score that is at least 80% of the maximum possible score (800). The results are saved in a pandas DataFrame named best_math_schools, which includes the "school_name" and "average_math" columns, sorted by "average_math" in descending order.

2. What are the top 10 performing schools based on the combined SAT scores?
The combined SAT score for each school is calculated by summing the average scores of math, reading, and writing. The top 10 schools based on these combined scores are saved in a pandas DataFrame named top_10_schools, which includes the "school_name" and "total_SAT" columns, sorted by "total_SAT" in descending order.

3. Which single borough has the largest standard deviation in the combined SAT score?
We analyze the standard deviation of the combined SAT scores for each borough. The borough with the largest standard deviation is identified and saved in a pandas DataFrame named largest_std_dev, which includes the columns "borough", "num_schools", "average_SAT", and "std_SAT".

Getting Started
Prerequisites
Python 3.x
pandas library
matplotlib library
Installation
Install the required Python libraries using pip:

bash
نسخ الكود
pip install pandas matplotlib
Usage
Clone the repository (if applicable) or download the dataset schools.csv and the analysis script.

Import necessary libraries


Summary
In this project, we analyzed the SAT performance of NYC high schools to address three key questions:

Identified the schools with the best math results: Schools with an average math score of at least 80% of the maximum possible score (800).
Determined the top 10 performing schools based on their combined SAT scores.
Found the borough with the largest standard deviation in combined SAT scores, providing insights into variability in performance within that borough.
This analysis offers valuable insights for stakeholders interested in the performance of NYC high schools.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
NYC Department of Education for providing the dataset.
All contributors and stakeholders in the education sector who use this analysis to make informed decisions.
