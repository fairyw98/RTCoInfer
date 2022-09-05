# MobileViT: Light-weight, General-purpose, and Mobile-friendly Vision Transformer

The implementation of paper : MobileViT: Light-weight, General-purpose, and Mobile-friendly Vision Transformer

## Data Resource
* Experiments are running on the dataset StanfordCars
* You may follow the data preparation guide [here](https://ai.stanford.edu/~jkrause/cars/car_dataset.html).
  
## Model Structure
View the model structure
```
./vitmodel.txt
```

## Running the experiments
Train the model, change the test_only to false
```
python swcnn_train.py app:apps/sw_mobilevit.yml
```
Test the model, change the test_only to true
```
python swcnn_train.py app:apps/sw_mobilevit.yml
```
and you can see the results in test_database.txt

