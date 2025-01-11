# Recession-Analysis-using-python
### Recession Analysis Made Simple

A **recession** happens when there’s less money moving around in the economy for **two consecutive quarters** (six months). This means people aren’t spending much, which causes businesses to lose money. When businesses lose money, they might lay off workers, leading to even less money being spent. You may have heard about such situations happening in 2023.

#### What is Recession Analysis?

To study a recession, we look at how much a country’s economy grows or shrinks. This can be checked using:
1. **GDP (Gross Domestic Product)**: The total value of goods and services a country produces.
2. **Unemployment Rate**: How many people don’t have jobs.
3. **Consumer Spending**: How much money people are spending.

In this case, we’re using **monthly GDP growth data** from the United Kingdom to study a recession.

---

### Steps to Analyze Recession

#### 1. **Import Data and Libraries**
We start by loading the data and tools in Python. The data has two columns: the time period and the GDP growth rate (how much the economy grew or shrank each month).

#### 2. **Visualizing GDP Growth**
We plot the GDP growth over time to see patterns. For example:
- Positive numbers mean growth.
- Negative numbers mean the economy is shrinking.

#### 3. **Convert Monthly Data to Quarterly Data**
Recessions are measured in **quarters** (3 months). So, we group the monthly data into quarters by averaging the GDP growth rates for every 3 months.

---

#### 4. **Identifying Recession**
A **recession** happens when the GDP growth is negative for two quarters in a row. We check this condition in Python:
- If GDP is negative for one quarter and the next one is also negative, it marks a recession.
- We plot the data, using:
  - **Green Line**: Shows overall GDP growth.
  - **Red Line**: Highlights recession periods.

---

#### 5. **Analyzing Recession Severity**
We also study how bad the recession is:
- **Duration**: How long the recession lasted.
- **Severity**: How much the economy shrank during the recession.

We plot:
- **Bars for Duration**: How many quarters the recession lasted.
- **Bars for Severity**: Total drop in GDP during that period.

---

### Summary
In simple words:
- A **recession** means the economy shrinks for 6 months straight.
- We study this by looking at GDP growth and identifying negative periods.
- By analyzing the data, we can see how long recessions last and how bad they get.

Using Python, we can find patterns in economic data and understand recessions better!
