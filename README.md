# emap-homework-4--p0-solved
**TO GET THIS SOLUTION VISIT:** [EMAP Homework 4- P0 Solved](https://www.ankitcodinghub.com/product/emap-your-boss-wants-you-to-import-some-csv-data-into-a-database-so-all-the-analysts-can-process-the-data-the-2-files-are-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124606&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EMAP Homework 4- P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Your boss wants you to import some CSV data into a database so all the analysts can process the data. The 2 files are

• customers.csv that contains customer information

• activities.csv that contains daily user activities.

1. Please create a database called demo.db using sqlite3 with 2 tables named customers and activities respectively.

2. You should have a sqlite3.Connection object called conn

3. You should have a sqlite3.Cursor object called cursor

4. Boolean values should be stored as TEXT

5. You should follow the class example where no primary keys are set and we do not set default values.

Hints:

In [1]:

from glob import glob import pandas as pd fns = glob(“./*.csv”)

print(fns)Assignment Project Exam Help

[‘./customers.csv’, ‘./activities.csv’]

In [2]:

# DO NOT REMOVE THE LINE ABOVE customers = pd.read_csv(“customers.csv”)

demo.db

conn=sqlite3.connect(“demo.db”) cursor = conn.cursor()

————————————————————————–NameError Traceback (most recent call last)

Cell In [1], line 6

4 customers = pd.read_csv(“customers.csv”)

5 activities = pd.read_csv(“activities.csv”)

—-&gt; 6 demo.db

7 conn=sqlite3.connect(“demo.db”)

8 cursor = conn.cursor()

NameError: name ‘demo’ is not defined

Exploring the databases and tables¶

1. Please use your cursor variable from above and write the SQL query that will return all the names of the tables in the demo.db database.

2. Please create a variable, tables, that is a list of strings where the string values are the table names (order does not matter).

3. Please use tables to create a dictionary called schema. schema should have keys corresponding to the table names and values corresponding to the output from the SQL query PRAGMA table_info(‘{TABLE_NAME}’)

In [3]:

### TEST FUNCTION: test_explore_db

# DO NOT REMOVE THE LINE ABOVE

In [4]:

Making some queries¶

Please answer all of the following questions using SQL queries, there is no need to call fetchall(). We will use your query in the testing.

In [5]:

### TEST FUNCTION: test_sql1

# DO NOT REMOVE THE LINE ABOVE query1 = “””

“””

In [6]:

Making some queries¶

string, to a variabled called Assignment Project Exam Helpquery2. Hint: check ‘subscriber’ defined in ‘customer’ and use JOIN

In [7]:

# DO NOT REMOVE THE LINE ABOVE query2 = “””

In [8]:

Makeing some queries¶

For each day, please calculate, in the following order:

• the number of unique visitors

• the total pageviews across all users

• the total likes across all users

• the total writes across all users

• the total activities across all users, total activities = total pageviews + total likes + total writes.

Please assign the query the answer to a variabled called query3.

In [9]:

### TEST FUNCTION: test_sql3

# DO NOT REMOVE THE LINE ABOVE connecton=sqlite3.connect(“demo.db”) cursor=connection.cursor()

query3 = “”” SELECT

COUNT(DISTINCT(activities.name)),

SUM(activities.pageviews),

SUM(COALESCE(activities.like,0)),

SUM(activities.writes),

SUM(COALESCE(activities.pageviews,COALESCE))

From activities

“””

output=cursor.execute(query).fetchall() output

In [10]:
