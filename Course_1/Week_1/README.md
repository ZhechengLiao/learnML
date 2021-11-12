# Learning Notes ("Week 1")
## Basic on Python
- Variable
- Advance Print
- Iteration and Condition
## Basic on Turi Create ("SFrames")
```python
import turicreate as tc
sf = tc.SFrame("people-sample.csv")
sf # Show the head of the csv
sf.head() # Same as the line 10
sf.tail() # Show the tail of the csv

sf.show() # Show the whole csv's visualized graph
sf['age'].show() # Show a particular part of the csv visualized graph

## Sort
```
## Case Study: Predicting House Price
### Linear Regression
- cost
- line
- overfitting
	- not good for new prediction
	- Do not need to be so specified 
- Term
	- Training set
	- Test set

