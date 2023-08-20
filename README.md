# dqe_great_expectations

## About this solution:
This solution helps with checks for employees table in TRN database

## Step-by-step setup guide:
First of all you need to clone this project:
```git
git clone https://github.com/VladYatsko/dqe-great-expectations.git
```

WHen you have project cloned on your local you need to execute:
```
pip install -r requirements.txt
```

To run current execution you can perform this command:
```
great_expectations checkpoint run test_checkpoint  
```

In case you need to configure datasource/assets you can manipulate with current files:
great_expectations.yml
test_checkpoint.yml

To configure expectations themselves you can collaborate with:
employees_expectations.json