**Task:** Predict the rating scores of the pairs (u, i) in the Test.txt file. 
**Dataset：**
(1)	Train.txt, which is used for training your models. 
(2)	Test.txt, which is used for test. 
(3)	ItemAttribute.txt, which is used for training your models (optional). 
(4) ResultForm.txt, which is the form of your result file. 

**DataFormatExplanation**
```
train.txt
<user id>|<numbers of rating items>
<item id>   <score>
test.txt
<user id>|<numbers of rating items>
<item id>
item.txt
<item id>|<attribute_1>|<attribute_2>('None' means this item is not belong to any of attribute_1/2)
```

The formats of datasets are explained in the DataFormatExplanation.txt. 
Note that if you can use ItemAttribute.txt appropriately and improve the performance of the algorithms, additional points (up to 10) can be added to your final course score. 


In this project, you need to report the predicted rating scores of the unknown pairs (u, i) in the Test.txt file. You can use any algorithms you have learned from the course or from other resources (such as MOOC). 
One group (consisting of at most three students) needs to write a report about this project. The report should include but not limited to the following contents: 
1.	Basic statistics of the dataset (e.g., number of users, number of ratings, number of items, etc.); 
2.	Details of the algorithms; 
3.	Experimental results of the recommendation algorithms (RMSE, training time, space consumption); 
4.	Theoretical analysis or/and experimental analysis of the algorithms. 

The deadline is June. 8, 2023.  （2023年6月8日晚上24点）

All your submitted assignments must be entirely your own groups. Any student found cheating or performing plagiarism will receive a final score of zero for this course.
