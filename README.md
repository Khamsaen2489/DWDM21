# DWDM21
Data Warehouse &amp; Data Mining 2021

Khamsaen Kaeophiphob 623020761-8

Grop แมวส้มสร้างตัว
1.คำแสน แก้วพิภพ
2.วานิตา สมเด็จ
3.จิตรกร จันทะสี 
4.อาธิติยา ธรรมวงษา
5.กรกนก สังฆพันธ์  

สารบัญ
บทที่ 1: Introduction

Introduction (บรรยาย)
Data Warehouse & Data Mining
Data Mining (การทำเหมืองข้อมูล)
Knowledge Discovery (KDD) Process
ขั้นตอนการทำเหมืองข้อมูล
เทคนิคของ Data Mining
บทที่ 2: Getting to Know Your Data

มิติของ Data (บรรยาย)
Basic Python
Varibles
Casting
Data Structure (list)
วิธีสร้าง list ว่าง
เติมค่าลงใน list (.append())
การชี้ค่าใน list (indexing)
list slicing
format string
Loop
Nested loop
Condition (if statment)
Function
normal
ไม่มี input
ไม่มี output
ไม่มีทั้ง input และ output
ลักษณะของ input (parameter)
Pandas
Read Data
.head() & .tail() (ดูหัวตาราง ท้ายตาราง)
Boxplot
Time Series plot
Visualization
Scatter plot
Normal
กำหนดขนาดจุด
กำหนดสี
เปลี่ยนลักษณะของจุดเป็นอย่างอื่น
Plot (เป็นการพล็อตกราฟที่เชื่อมกัน)
Bar Chart
Grouped Barchart (พล็อตเทียบด้านข้าง)
Stacked Barchart (พล็อตเทียบในแท่งเดียวกัน)
Histogram
Distance Numpy
Numpy Array
สร้าง numpy array (matrix)
matrix transpose
สร้าง matrix เริ่มต้น (zeros,ones)
สร้าง matrix random
matrix properties
matrix properties
Useful functions
เขียน function วนลูปหา sum, mean, max, min
Distance Matrix
Euclidean Distance (L2-norm)
Distance function
Manhattan Distance (L1-norm)
Distance of Binary Value
บทที่ 3: Data Preprocessig

Data Preprocessig
การชี้ข้อมูลในตาราง
ชี้แบบธรรมดา [ชื่อคอลัมน์][index]
ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
Missing Values
Handling Missing value 1 (ลบค่า missing)
เขียน function หาว่าการทำ dropna() ทำให้ข้อมูลหายไปกี่ %
Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown))
Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
Handling Missing Value 4 (แทนด้วย ค่ากลาง)
Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
Select data by values [PD]
สร้าง list ของ boolean
นำ list ของ boolean มาเลือกค่าในตาราง
ต่อตางแนวแกน Y [PD]
Handling Missing Value 5 (แทนด้วย ค่ากลางของ sample ใน class เดียวกัน) ต่อ
การเรียงข้อมูล [PD]
หา Outlier
เขียนฟังค์ชั่น คำนวณ หา Q1,Q2,Q3,IQR,vmin,vmax โดยรับ input เป็น output ขอบ boxplot
เขียน function box_vals ให้สามารถรับ input ที่ box plot วาดแบบแนวนอนได้ (vert = False)
Panda's looping (.ilerrows)
การรวมตาราง (ต่อตารางในแนวแกน x)
รวม 2 ตาราง (.merge())
เลือกมาเฉพาะ column ที่ต้องการมาแปะ (.map())
Group by (pandas)
[PD] save ตารางเอาไปใช้ที่อื่น
[PD] การสร้างตาราง
บทที่ 4: Data Warehousing and On-line Analytical Processing

บทที่ 5: Association Rules

Mining Frequent Patterns, Association and Correlations (บรรยาย)
What Is Pattern Discovery
Basic Concepts
Apriori
Data 'reduced_marketbasket' Case
HW
มีประเทศสาขาของ Supermarket นี้ทั้งหมดกี่ประเทศ
วาดกราฟสรุปจำนวน items และ ยอดขายของแต่ละประเทศ
เพิ่มคอลัมน์ ยอดขาย (Quantity x UnitPrice)
จัดกลุ่มและหายอดขายรวม
จัดกลุ่มและหายอดขายรวม
เรียนต่อ
ลบ records ที่ถูก cancel ออกไป
เตรียม data สำหรับ (Fequence Pattern) Association Rule
Apriori
บทที่ 6: Classification

Classification: Basic Concepts (บรรยาย)
Supervised vs Unsupervised Learning
Clssification vs Numeric Prediction
Classification-Model Construction, Validation and Testing
Decision Tree Induction
Information Gain
Decision Tree คำนวนมือ (บรรยาย การบ้าน)
Decision Tree
Load Data
Train Model
import (เรียกใช้ algorithm ที่เราต้องการ)
Define (กำหนด parameters ให้กับ model)
train (ฝึกสอนตัวแบบ)
plot tree
Advanced Tree
ใช้ค่า Default
import
Define
Train
Evaluate
ต้นไม้ที่ใช้เกณฑ์ Entropy มีความสูงไม่เกิน 4 ชั้น
ต้นไม้ที่ใช้เกณฑ์ Gini มีใบไม่เกิน 25 ใบ
ต้นไม้ที่ใช้เกณฑ์ Entropy และใช้การ split แบบ random
ต้นไม้ที่ใช้เกณฑ์ Entropy และ ใช้การ split แบบ random และ ข้อมูลที่อยู่ในใบขั้นต่ำ = 2 และ เริ่ม random ที่จุดที่ 6
K-Nearest Neighbor & Neural Network
Load data
Split Data
K-Nearest Neighbor (KNN)
Trian Model
import
knn1 (ถามเพื่อนบ้านที่ใกล้สุด 3 คน และเชื่อทุกคนเท่าๆ กัน)
knn2 (ถามเพื่อนบ้านที่ใกล้ที่สุด 10 คน และเชือคนที่อยู่ใกล้มากกว่าอยู่ไกล)
knn3 (เชื่อเพื่อนบ้านที่ใกล้ที่สุด 1 คน)
Retrain & Evaluate
Neural Network
inport
Define
Train-Test
Evaluation
Load data
แบ่ง Data
สร้าง Model ทำนาย
Import
Define
Train
Evaluation (classification_report, confusion_matrix, accuracy_score)
บทที่ 7: Clustering

Clustering
K-means
Generate Data
Explore data
Clustering
Import
Define
Fit-Predict
Example application (Color Quantization) (ลดจำนวนสีของภาพ)
นับจำนวนสี
จัดกลุ่มสีให้เหลือ 16 สี
แปลงข้อมูลให้อยู่ในรูป row-column
ใช้ centroid เป็นตัวแทนของสี
การแทนสีคืนลงไป
MiniExam

Data flights and airports Case
หารัฐที่มีจำนวนเครื่องบินขาออกมากที่สุดและน้อยที่สุด
สายการบินอะไรมีความล่าช้ามากที่สุดและน้อยที่สุด
เปรียบเทียบความล่าช้าของการบินในแต่ละวัน
Project Group

Project Group
Data and Preprocessing
ปัญหา
Association Rules
Classification
Split Data
Decision Tree
KNN
Neural Network
Retrain & Evaluate
Visualization
เปรียบเทียบจำนวนสินค้าที่ขายได้ในแต่ล่ะ category
เปรียบเทียบ ราคา,ค่าส่ง,ความสูง,ความยาว,น้ำหนัก และ ความกว้าง เฉลี่ย ของแต่ล่ะ category
Slide นำเสนอ
