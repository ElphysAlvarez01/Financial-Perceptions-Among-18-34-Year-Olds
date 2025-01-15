# Economic Insights: Exploring Financial Perceptions of 18-34-Year-Olds

### **Quick Summary:** 

**Overview:** This analysis examines responses from individuals aged 18-34 to personal finance questions from the University of Michigan’s Surveys of Consumers. Visualization for other demographic groups is available; however, I have concentrated on individuals aged 18-34 for this analysis. 

**Visualization:** The data is restructured using Tableau to focus on key recession periods (2001, 2007-09, 2020) and the current economic outlook in 2024. 

**Analyses Conducted:** Tableau was used to conduct predictive models like forecasts and linear regression. The models provided insights into the "Current Financial Situation," "Expected Changes," and "Probabilities of Income Gains and Job Loss."

**Link to Tableau Public Dashboard / Story:**  ADD IT HERE! 

----------------------------------------------------------------------------------------------------------

### **Data Preparation:** 

- Data was downloaded from The University of Michigan’s Surveys of Consumers site ( [https://data.sca.isr.umich.edu/subset/subset.php]) at the end of December 2024. However, the data is as of **XX/XX/XXXX**.
- The data was then restructured to include a column per personal finance question. The original file separated the responses for each demographic individual (e.g. 18-34, 35-54, 55-97) by personal finance question.
- Using Tableau, the data was pivoted to allow for filtering by demographic groups and personal finance question type.
- Tableau was also used to create groups by personal finance questions by type (e.g. Current Situation Comparison, Expectation of the Future, and Probabilities).

### ADD IMAGE EXAMPLE:

**Helpful Calculations Used:** 
- XX
- XX

**Visualization Notes:** 
- To ensure the charts are not overwhelming, only specific periods were highlighted to show the labels. A calculation with recession dates was created to label dates as "Normal" or "Highlight" periods. 
- Other periods that were displayed were the lowest and highest scores.
  
----------------------------------------------------------------------------------------------------------

## **Series of Analyses:**

### 1. Current Financial Situation

**Key Insights:**

•	**Lowest Confidence:** During the Great Recession, the 1-year ago comparison confidence dropped to 77, and the 5-years ago comparison dropped to 108, and then it took a decade to recover. The 2020 pandemic recession triggered another decline, with scores now at 100 and 135 in 2024, respectively. 

•	**Highest Confidence:** For 1-year ago comparisons, confidence peaked in 1997 at 156 but stayed relatively the same until 2001 when it dropped to 141 and then continued down until 2002. Scores did not recover until 2019 Q4, before the 2020 pandemic recession. For the 5-year ago comparison, the score peaked at 172, before the 2001 recession. The 2020 pandemic recession triggered another decline, with scores now at 100 and 135 in 2024, respectively.

**Linear Regression:** ADD INFORMATION HERE!


### 2. Expected Changes in Financial Situation: 

**Key Insights:**
•	Current Expectations (2024): The 1-year outlook stands at 133, close to its post-2008 low of 122, signaling minimal optimism. The 5-year outlook has fallen to 150, the lowest since the pandemic recovery began.

•	Pandemic Highs: Interestingly, expectations were more optimistic during the pandemic in 2020, with the 5-year outlook at 161, highlighting hope for rapid recovery at the time.

**Linear Regression:** ADD INFORMATION HERE!


### 3. Probabilities: Income Gains vs. Job Loss

**Probability of Income Gains:**
•	Current Outlook (2024): Confidence in income gains over the next 5 years is just 9, lower than during the 2020 pandemic recession, reflecting pessimism about wage growth and economic mobility.

•	Historical Comparison: This score is far below the 56 seen during the 1990s boom and closer to the low of -23 in 2009.

**Probability of Job Loss:**
•	The current outlook as of 2024 Q4, the perception of the probability of Job Loss is at 27, and it has remained elevated, similar to pandemic levels, reflecting continued instability in the labor market.

•	Historical Trends: While lower than the peak of 37 in 2020, the score highlights lingering concerns about economic security, even as unemployment rates nationally remain low.

**Linear Regression:** ADD INFORMATION HERE!

----------------------------------------------------------------------------------------------------------

### Future Research
As of 2024 Q4, ETFs (e.g., SPY) and the magnificent 7 are at all-time highs and returning double digits annually, and yet we still see low confidence and perceptions of personal finances. This makes me wonder what factors would help individuals feel more positive about personal finances. Future Research should look at:
 
1.	**The relationship between  personal finance questions and other factors such as layoffs, job openings, wage growth, inflation, and stock allocations.** Economic uncertainty, layoffs, and slow wage growth can weigh on young adults' financial outlook and exacerbate concerns about economic security.

2.	**Analyze the same information but with other demographic breakdowns such as income and education levels.** Perhaps other demographic groups feel the economic insecurity less or later in the cycle. 

3.	**It would also be interesting to assess how changes in personal finance confidence influence presidential results.** For example, the 2024 presidential results were recently finalized and as we know from this analysis, most personal finance questions showed confidence decreasing during the last 4 years compared to late 2019 and early 2020. Future Research should assess how presidential results influence confidence levels during the tenure of the sitting president. 

4. **Lastly, it would be helpful to identify Seasonal Cycles** - Identifying seasonal cycles would be helpful for economists and policymakers. Perhaps there are confidence lows or highs that occur during specific quarters, or months.

----------------------------------------------------------------------------------------------------------

### Usage: The results should be particularly interesting for policymakers as it would also be critical to understand demographic groups (e.g., regional, education, and income) to help improve their perceptions and confidence levels of their finances. 

### Conclusion:

The financial confidence and expectations of individuals aged 18-34 have been profoundly shaped by economic cycles. While the current outlook in 2024 shows improvement compared to previous recession lows, it remains subdued relative to the highs before the 2020 pandemic recession which caused a sharp decline in confidence and expectations over the past four years. 

## Assumptions and Caveats:
- Please note that certain personal questions either started later than other questions or they seem to have had a pause. I displayed the time series as is with those periods missing. 
- Data was also rounded to the nearest whole across the visualizations to make it easier to read.
