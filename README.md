<h1>📊 Statistics for Data Science</h1>

<p>Statistics helps us understand, analyze, and interpret data. It is broadly divided into:</p>
<ul>
  <li><strong>Descriptive Statistics</strong> – Summarizes and describes data</li>
  <li><strong>Inferential Statistics</strong> – Draws conclusions about a population from sample data</li>
</ul>

<hr>

<h2>🔹 DESCRIPTIVE STATISTICS</h2>

<p>Descriptive statistics describe the main features of a dataset.</p>

<h3>1️⃣ Measures of Central Tendency</h3>
<p>These measures represent the center or typical value of a dataset.</p>

<h4>➤ Mean</h4>
<p>The mean is the average of all values.</p>
<p><strong>Formula:</strong> Mean = (Sum of all values) / (Number of values)</p>
<p><strong>Example:</strong></p>
<pre>
Data = 10, 20, 30, 40, 50
Mean = 30
</pre>
<p>Best used when the data has no extreme values.</p>

<h4>➤ Median</h4>
<p>The median is the middle value when data is arranged in ascending order.</p>
<p><strong>Example (Odd count):</strong></p>
<pre>
Data = 10, 20, 30, 40, 50
Median = 30
</pre>
<p><strong>Example (Even count):</strong></p>
<pre>
Data = 10, 20, 30, 40
Median = 25
</pre>
<p>Useful when data contains outliers.</p>

<h4>➤ Mode</h4>
<p>The mode is the value that appears most frequently.</p>
<p><strong>Example:</strong></p>
<pre>
Data = 2, 3, 3, 5, 7
Mode = 3
</pre>

<hr>

<h3>2️⃣ Measures of Dispersion</h3>
<p>These measures show how spread out the data is.</p>

<h4>➤ Range</h4>
<p>The difference between the maximum and minimum values.</p>
<p><strong>Formula:</strong> Range = Max − Min</p>
<pre>
Data = 10, 20, 30, 40
Range = 30
</pre>

<h4>➤ Percentile</h4>
<p>A percentile indicates the value below which a given percentage of observations fall.</p>
<p><strong>Example:</strong> 90th percentile means 90% of data lies below that value.</p>

<h4>➤ Quantile</h4>
<p>Quantiles divide data into equal-sized parts.</p>
<ul>
  <li>Q1 – 25%</li>
  <li>Q2 – 50% (Median)</li>
  <li>Q3 – 75%</li>
</ul>

<h4>➤ Interquartile Range (IQR)</h4>
<p>Measures the spread of the middle 50% of data.</p>
<p><strong>Formula:</strong> IQR = Q3 − Q1</p>
<pre>
Q1 = 20, Q3 = 40
IQR = 20
</pre>

<h4>➤ Outliers</h4>
<p>Outliers are values that lie far away from most data points.</p>
<p><strong>Rule:</strong></p>
<ul>
  <li>Below Q1 − 1.5 × IQR</li>
  <li>Above Q3 + 1.5 × IQR</li>
</ul>

<h4>➤ Variance</h4>
<p>Variance measures how far data points are from the mean.</p>
<p>It is expressed in squared units.</p>

<h4>➤ Standard Deviation</h4>
<p>The square root of variance.</p>
<p>Shows how much values typically deviate from the mean.</p>

<hr>

<h3>3️⃣ Z-Score</h3>
<p>The Z-score indicates how many standard deviations a value is from the mean.</p>
<p><strong>Formula:</strong> Z = (x − μ) / σ</p>
<pre>
Mean = 50, SD = 10, Value = 70
Z = 2
</pre>
<p>A Z-score of 2 means the value is two standard deviations above the mean.</p>

<hr>

<h3>4️⃣ Normal Distribution</h3>
<p>A normal distribution is a bell-shaped and symmetric distribution.</p>
<ul>
  <li>Mean = Median = Mode</li>
  <li>68% of data lies within ±1 SD</li>
  <li>95% of data lies within ±2 SD</li>
  <li>99.7% of data lies within ±3 SD</li>
</ul>

<hr>

<h2>🔹 INFERENTIAL STATISTICS</h2>

<p>Inferential statistics help make predictions or decisions about a population based on sample data.</p>

<h3>1️⃣ Covariance</h3>
<p>Covariance measures the direction of the relationship between two variables.</p>
<ul>
  <li>Positive covariance: variables increase together</li>
  <li>Negative covariance: one increases while the other decreases</li>
  <li>Zero covariance: no relationship</li>
</ul>

<h3>2️⃣ Correlation</h3>
<p>Correlation measures both the strength and direction of the relationship.</p>
<p>Correlation values range from -1 to +1.</p>

<h4>➤ Pearson Correlation</h4>
<p>Measures the linear relationship between two continuous variables.</p>
<p><strong>Example:</strong> Height vs Weight</p>
<p>Used when data is normally distributed and the relationship is linear.</p>

<h4>➤ Spearman Rank Correlation</h4>
<p>Measures the monotonic relationship using ranks.</p>
<p><strong>Example:</strong> Student rank vs exam score</p>
<p>Used when data is not normally distributed or is ordinal.</p>

<hr>

<h3>📌 Summary</h3>
<table border="1" cellpadding="6">
  <tr>
    <th>Concept</th>
    <th>Purpose</th>
  </tr>
  <tr><td>Mean</td><td>Average value</td></tr>
  <tr><td>Median</td><td>Middle value</td></tr>
  <tr><td>Mode</td><td>Most frequent value</td></tr>
  <tr><td>Range</td><td>Max − Min</td></tr>
  <tr><td>IQR</td><td>Middle 50% spread</td></tr>
  <tr><td>Variance</td><td>Dispersion of data</td></tr>
  <tr><td>Standard Deviation</td><td>Spread from mean</td></tr>
  <tr><td>Z-Score</td><td>Relative position</td></tr>
  <tr><td>Covariance</td><td>Direction of relationship</td></tr>
  <tr><td>Pearson</td><td>Linear correlation</td></tr>
  <tr><td>Spearman</td><td>Rank-based correlation</td></tr>
</table>
