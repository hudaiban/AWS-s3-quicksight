# AWS-s3-QuickSight

# Steps to  Visualize Data using S3 and QuickSight 

1- Download both .csv and .json files 
2- Open the console 
3- Navigate to S3 create bucket (You name it)
4- Navigate to the bucket and upload .csv
5- Open .json file and update line 5 (URI) to your .csv file (file in which you want to visualize)
6- Save them, and upolad .json file to S3
7- open new tap navigate to QuickSight (if first time activate  it but don't forget to delete within a month)
8-  Create new Dataset -> choose S3 
9- Go back to S3 bucket -> manifest.json file and copy URl and paste it within the uploading pop up 
10- Connect 

## Finally will be seeing your file dataset visualized with QS