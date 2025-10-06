# BigDataAnalytics

A repository of PySpark / Big Data Analytics notebooks, example datasets, and mini-projects.  
This project is aimed at demonstrating common PySpark operations, data transformations, sampling, analytics, and a mini project on Studentexamscores data analysis.

---

## 📂 Repository Structure

```
├── 1.DataTransformation Using PySpark RDD
│ ├── Pyspark_Even_Number_Filter.ipynb
│ └── students.xls
├── 2.Collect() Operation with RDD Operation
│ ├── PySpark_Student_Data_Analysis_with_RDDs.ipynb
│ └── students.xls
├── 3.Sample() and TakeSample() Methods
│ ├── Exploring_and_Transforming_Data_with_PySpark_DataFrames.ipynb
│ └── students.xls
├── 4.Exploring Structure And Contents of CSV File
│ ├── Basic_Operations_on_PySpark_DataFrames.ipynb
│ └── students.xls
├── 5.Viewing Data And Selecting Columns Of CSV File
│ ├── Data_Sampling_in_PySpark_DataFrames.ipynb
│ └── students.xls
├── 6.Analytical Operations on CSV File
│ ├── Performing_Analytical_Operations_in_PySpark.ipynb
│ └── students.xls
└──7.StudentExamScoresAnalysis
     ├── StudentexamscoreAnalaysis.ipynb
     ├── student_exam_scores.csv
     ├── Student_Exam_Score_Analysis_Report.docx
     └── .ipynb_checkpoints/
```

Here’s a brief on what each folder covers:

**1.DataTransformation Using PySpark RDD** — shows how to filter RDDs (e.g. extract even numbers)  
**2.Collect() Operation with RDD Operation** — operations using `collect()` to bring data to driver  
**3.Sample() and TakeSample() Methods** — sampling methods in Spark DataFrames / RDDs  
**4.Exploring Structure And Contents of CSV File** — basic DataFrame operations (read, print schema, etc.)  
**5.Viewing Data And Selecting Columns Of CSV File** — selecting, filtering, sampling in DataFrames  
**6.Analytical Operations on CSV File** — aggregate operations, groupBy, statistics  
**7.StudentExamScoresAnalysis** — a focused end-to-end example: loading studentexamscores data, filtering, analysis, generating reports  

---

## 🛠️ How to Use / Run

### Prerequisites

- Python (3.x)  
- Apache Spark (compatible version)  
- Jupyter Notebook / JupyterLab (or another notebook environment)  

### Steps

- Clone this repository:
   ```bash
   git clone 
   cd BigDataAnalytics
- Start Spark + Jupyter (for example, with pyspark --master local[*] --packages … or using spark-submit / your Spark environment).
- Open the desired notebook (e.g. 1.DataTransformation Using PySpark RDD/Pyspark_Even_Number_Filter.ipynb) and run code cells sequentially.
- For the mini project (folder 7.Studentscores Data Analysis Using PySpark (Mini Project)), follow the notebook instructions, and refer to the provided datasets and deliverables (report, PPT, etc.).

### Features & Highlights

Demonstrates working with RDDs and DataFrames

Shows data transformations, filtering, sampling, aggregations

Mini project as a real-world use case: studentexamscores data analytics

Datasets included so you can run examples end-to-end
