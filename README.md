# dqe_great_expectations

## About this solution:
This solution helps with checks for employees table in TRN database

## Step-by-step setup guide:
First of all you need to clone this project:
```
pip install -r requirements.txt
```

After all the actions above are performed you can run tests with three ways:
1) With default Python commands from framework root folder: 
```
pytest --alluredir=results --reruns 5 .\tests\   
```
After tests are finished you need to run:
```
allure serve results 
```
To generate allure report.

2) With running test_runner.bat for Windows to avoid typing commands 2 times.
3) For Unix/macOS there is test_runner.sh file, but to run it you need first run
```bash
chmod +x ./test_runner.sh
```
Then execute file with similar snippet as for Windows OS.
