# HR_Analytics_Excel_Dashboard
An interactive HR Analytics Dashboard built using Power BI to analyze employee attrition, job satisfaction, and workforce trends. It highlights high-risk roles, departments, and key KPIs to support data-driven HR decisions and improve employee retention

<h2>Project Overview</h2>
    <p>
      This project utilizes organizational HR data to conduct a deep analysis of employee
      behavior, satisfaction, and performance metrics. The primary objective is to identify
      factors contributing to attrition, understand the relationship between job satisfaction
      and employee roles, and provide data-driven recommendations to improve retention and
      overall workforce performance.
    </p>

    <h2>Problem Statement</h2>
    <ul>
      <li>
        What are the primary demographic, job-related, and satisfaction factors that
        correlate most strongly with Attrition (Yes/No)?
      </li>
      <li>
        How do key metrics like Monthly Income, Total Working Years, and Years At Company
        differ between employees who stay and those who leave?
      </li>
      <li>
        Which departments and job roles show the highest risk of attrition, especially when
        combined with factors like Over Time?
      </li>
      <li>
        How does the Performance Rating relate to Percent Salary Hike and job satisfaction
        metrics?
      </li>
    </ul>

    <h2>Technology Stack</h2>
    <p>
      <strong>Data Storage:</strong> CSV File<br>
      <strong>Visualization:</strong> Power BI
    </p>

    <h2>Key Performance Indicators (KPIs)</h2>
    <table>
      <thead>
        <tr>
          <th>KPI</th>
          <th>Business Significance</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Attrition Rate</td>
          <td>The most critical measure of workforce stability.</td>
        </tr>
        <tr>
          <td>Average Tenure</td>
          <td>Indicates long-term employee engagement and retention success.</td>
        </tr>
        <tr>
          <td>Engagement Score</td>
          <td>Measures how connected and happy employees are.</td>
        </tr>
        <tr>
          <td>Performance Gap</td>
          <td>Identifies high and low-performing organizational units.</td>
        </tr>
        <tr>
          <td>Salary Hike Effectiveness</td>
          <td>Tests if compensation increases are adequately motivating employees to stay.</td>
        </tr>
      </tbody>
    </table>

    <h2>Chart Requirements and Analysis</h2>
    <table>
      <thead>
        <tr>
          <th>Chart Type</th>
          <th>Analysis Goal</th>
          <th>Data Columns Required</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Density / Box Plots</td>
          <td>Income and experience distribution by Attrition</td>
          <td>Monthly Income, Total Working Years, Attrition</td>
        </tr>
        <tr>
          <td>Bar Chart</td>
          <td>Attrition by Job Role, Department, Marital Status, Over Time</td>
          <td>Attrition, Categorical Features</td>
        </tr>
        <tr>
          <td>Scatter Plot</td>
          <td>Distance From Home vs Attrition</td>
          <td>Distance From Home, Attrition</td>
        </tr>
        <tr>
          <td>Heatmap</td>
          <td>Correlation among satisfaction metrics</td>
          <td>Numerical Satisfaction Columns</td>
        </tr>
        <tr>
          <td>Pie / Donut Chart</td>
          <td>Attrition by Age Group</td>
          <td>Attrition, CF Age Band</td>
        </tr>
      </tbody>
    </table>

    <h2>Key Insights & Recommendations</h2>

    <h3>Key Insights</h3>
    <ul>
      <li><strong>Overtime Crisis:</strong> Employees working overtime show 3× higher attrition.</li>
      <li><strong>Compensation Sensitivity:</strong> Higher attrition below $5,000/month salary.</li>
      <li><strong>High-Risk Roles:</strong> Laboratory Technicians and Sales Representatives.</li>
      <li><strong>Tenure Risk:</strong> Highest attrition occurs at 3–5 years of service.</li>
    </ul>

    <h3>Recommendations</h3>
    <ul>
      <li><strong>Mandatory Overtime Audit:</strong> Introduce flex-time or compensatory leave.</li>
      <li><strong>Targeted Compensation Review:</strong> Improve low salary bands.</
