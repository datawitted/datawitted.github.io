<div style="display: flex; justify-content: space-between; align-items: center; background-color: #D9F2F9; padding: 20px;">
    <div style="flex: 1; text-align: center;">
        <img src="/asset/OLASUNKANMI_HEADSHOT.png" alt="Profile Picture" style="width: 150px; height: 150px; border-radius: 50%; border: 3px solid #023046; background-color: #2D6DC2;">
    </div>
    <div style="flex: 1; text-align: center; color: #023046;">
        <h1 style="font-size: 2.5rem; margin: 0;">Olasunkanmi Aremu</h1>
        <p style="font-size: 1.25rem;">Data Analyst | Python | SQL | AWS | Snowflake | MATLAB</p>
    </div>
</div>

<nav style="background-color: #023046; padding: 10px; text-align: center;">
    <a href="#about" style="color: #D9F2F9; margin-right: 20px;">About Me</a>
    <a href="#experience" style="color: #D9F2F9; margin-right: 20px;">Experience</a>
    <a href="#education" style="color: #D9F2F9; margin-right: 20px;">Education</a>
    <a href="#projects" style="color: #D9F2F9; margin-right: 20px;">Projects</a>
    <a href="#publications" style="color: #D9F2F9; margin-right: 20px;">Publications</a>
</nav>

<div id="about" style="background-color: white; padding: 20px; color: #023046;">
    I am a data analyst with a background in digital marketing. Motivated by the power of data, I transitioned to this field and gained proficiency in SQL, Python, Power BI, Tableau, and Excel. My goal is to help businesses make data-driven decisions that drive growth and efficiency.
</div>

<div id="experience" style="background-color: #D9F2F9; padding: 20px; color: #023046;">
    <h2 style="color: #D9F2F9; background-color: #023046; padding: 10px; display: inline-block; width: 100%;">Experience</h2>
    <p><strong>Data Scientist @ Toyota Financial Services (<em>June 2022 - Present</em>)</strong></p>
    <ul>
        <li>Uncovered and corrected missing step in production data pipeline which impacted over 70% of active accounts</li>
        <li>Redeveloped loan originations model which resulted in 50% improvement in model performance and saving 1 million dollars in potential losses</li>
    </ul>
    <p><strong>Data Science Consultant @ Shawhin Talebi Ventures LLC (<em>December 2020 - Present</em>)</strong></p>
    <ul>
        <li>Conducted data collection, processing, and analysis for novel study evaluating the impact of over 300 biometrics variables on human performance in hyper-realistic, live-fire training scenarios</li>
        <li>Applied unsupervised deep learning approaches to longitudinal ICU data to discover novel sepsis sub-phenotypes</li>
    </ul>
</div>

<div id="education" style="background-color: #D9F2F9; padding: 20px; color: #023046;">
    <h2 style="color: #D9F2F9; background-color: #023046; padding: 10px; display: inline-block; width: 100%;">Education</h2>
    <p><strong>Ph.D., Physics | The University of Texas at Dallas (<em>May 2022</em>)</strong></p>
    <p><strong>M.S., Physics | The University of Texas at Dallas (<em>December 2019</em>)</strong></p>
    <p><strong>B.S., Physics | The University of Texas at Dallas (<em>May 2017</em>)</strong></p>
</div>
    
<div id="projects" style="background-color: #D9F2F9; padding: 20px; color: #023046;">
    <h2 style="color: #D9F2F9; background-color: #023046; padding: 10px; display: inline-block; width: 100%;">Projects</h2>
<!-- Add this code within your project content -->
<h3>Personal Finance Tracker</h3>
<p><strong>Situation</strong></p>
<ul>
        Many individuals struggle with managing their personal finances. They may not have the necessary tools or knowledge to effectively budget and make informed financial decisions. Additionally, traditional personal finance software can be expensive and difficult to use.
    </ul>
    <p><strong>Task</strong></p>
    <ul>
        To address this issue, I developed a Python program that allows individuals to easily manage their personal finances. My role in the project was as the sole developer.
    </ul>
    <p><strong>Action</strong></p>
    <ul>
        I utilized Python to create a user-friendly program that allows individuals to input their income and expenses, categorize their spending, and track their financial progress over time. The program includes a dashboard that displays the user's spending habits and provides tips for improving their finances. The code is available below.

To create this program, I utilized the following tools and techniques:
<li>Python</li>
<li>Pandas library for data manipulation</li>
    </ul>
    <pre>
# sample code block
import pandas as pd
import matplotlib.pyplot as plt

# read in data
df = pd.read_csv('expenses.csv')

# group expenses by category
expenses_by_category = df.groupby('category')['amount'].sum()

# create pie chart of expenses by category
plt.pie(expenses_by_category, labels=expenses_by_category.index)
plt.title('Expense Breakdown by Category')
plt.show()
</pre>
<button class="popup-button" onclick="openPopup()">View Code</button>

<!-- Add this code at the end of your HTML file, before the closing </body> tag -->
<div id="popup" class="popup">
    <div class="popup-content">
        <span class="close-button" onclick="closePopup()">&times;</span>
        <pre>
            <!-- Your code block goes here -->
            # sample code block
            import pandas as pd
            # ... Rest of your code ...
        </pre>
    </div>
</div>



 <h3>Personal Finance Tracker</h3>
    <p><strong>Situation</strong></p>
    <ul>
        Many individuals struggle with managing their personal finances. They may not have the necessary tools or knowledge to effectively budget and make informed financial decisions. Additionally, traditional personal finance software can be expensive and difficult to use.
    </ul>
    <p><strong>Task</strong></p>
    <ul>
        To address this issue, I developed a Python program that allows individuals to easily manage their personal finances. My role in the project was as the sole developer.
    </ul>
    <p><strong>Action</strong></p>
    <ul>
        I utilized Python to create a user-friendly program that allows individuals to input their income and expenses, categorize their spending, and track their financial progress over time. The program includes a dashboard that displays the user's spending habits and provides tips for improving their finances. The code is available below.

To create this program, I utilized the following tools and techniques:
<li>Python</li>
<li>Pandas library for data manipulation</li>
    </ul>
    <pre>
# sample code block
import pandas as pd
import matplotlib.pyplot as plt

# read in data
df = pd.read_csv('expenses.csv')

# group expenses by category
expenses_by_category = df.groupby('category')['amount'].sum()

# create pie chart of expenses by category
plt.pie(expenses_by_category, labels=expenses_by_category.index)
plt.title('Expense Breakdown by Category')
plt.show()
</pre>
    <img src="/asset/preambule_money_pro_android.jpg" alt="EEG Band Discovery" style="width: 100%; height: auto;">
</div>

<div id="talks" style="background-color: #D9F2F9; padding: 20px; color: #023046;">
    <!-- Talks & Lectures content here -->
</div>

<div id="publications" style="background-color: white; padding: 20px; color: #023046;">
    <!-- Publications content here -->
</div>
