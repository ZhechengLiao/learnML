# Week 2
## Step 1: Advance show
- `tc.show(data_set[1:5000]['sqft_living'], data_set[1:5000]['price']`
## Step 2: Split Train and Test
`sqft_model = tc.linear_regression.create(train_set, target="price", feature=['sqft_living'])`
## Setp 3: Evaluate
`print(sqft_model.evaluate(test_set))`
## Step 4: Show the prediction look like
## Step 5: More features

