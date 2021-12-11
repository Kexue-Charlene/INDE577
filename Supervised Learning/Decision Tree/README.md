# Decision Tree

Decision Tree is one of the most widely used supervised machine learning algorithm. Decision tree learning is used for classification and regression. The decision tree algorithm works like a human brain every time we ask a question ourselves before making a certain decision. For example, older than 30? If yes, eat pizza? If no, exercise. The decision tree takes the training set and split up it into the smaller subsets based on features.
<td> <img src="https://lh4.googleusercontent.com/v9UQUwaQTAXVH90b-Ugyw2_61_uErfYvTBtG-RNRNB_eHUFq9AmAN_2IOdfOETnbXImnQVN-wPC7_YzDgf7urCeyhyx5UZmuSwV8BVsV8VnHxl1KtgpuxDifJ4pLE23ooYXLlnc" width="400"/> </td>

## Decision Tree Algorithm
A decision tree is a flowchart-like tree structure where an internal node represents feature(or attribute), the branch represents a decision rule, and each leaf node represents the outcome. The topmost node in a decision tree is known as the root node. 

How does the decision tree algorithm work?
1. Select the best attribute using Attribute Selection Measures(ASM) to split the records.
2. Make that attribute a decision node and breaks the dataset into smaller subsets.
3. Starts tree building by repeating this process recursively for each child until one of the condition will match:
    * All the tuples belong to the same attribute value.
    * There are no more remaining attributes.
    * There are no more instances.
 <td> <img src="https://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1545934190/1_r5ikdb.png" width="400"/> </td>
 
# Reference 

Akshay, Chavan. AI TIME JOURNAL, A Comprehensive Guide to Decision Tree Learning, Feb,7,2019. https://www.aitimejournal.com/@akshay.chavan/a-comprehensive-guide-to-decision-tree-learning

Jason, Brownlee. What is a Confusion Matrix in Machine Learning, Nov,18,2016. https://machinelearningmastery.com/confusion-matrix-machine-learning/

Avinash, Navlani. Decision Tree Classification in Python. Dec,28th,2018. https://www.datacamp.com/community/tutorials/decision-tree-classification-python
