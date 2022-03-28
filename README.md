# Amazon_Vine_Analysis

# Big Data

## Overview of Project

### Purpose

The purpose of this project is to work with handle large amounts of data using cloud based infastructure. We are using AWS RDS to create a Postgres database that we will be connecting to an managing using PGadmin which will let us have access to a database without having a local server running. Also we will be using google Colab which is a cloud based environment that will execute python code so we can interface and send data to the postgres database that we created on AWS.

## Results

- How many Vine reviews and non-Vine reviews were there?

Total vine reviews were 94. The image below shows the code that calculation.

![image](https://user-images.githubusercontent.com/92827264/160320627-323c6f3f-5a99-4bae-9480-e8df5b85df1a.png)

Total non-vine reviews are 40471. The image below shows the code to get the data.

![image](https://user-images.githubusercontent.com/92827264/160320838-94c25a3c-6c86-4d45-919f-c9f8fec790d6.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

5 Star vine reviews: 48 

![image](https://user-images.githubusercontent.com/92827264/160320936-0a26ee89-7ba1-4da5-adb8-a9038c31d4b8.png)

5 Start non-vine reviews: 15663

![image](https://user-images.githubusercontent.com/92827264/160320993-3182109a-3de5-4948-9ba5-3fb0a720d134.png)


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

5 Star vine review percentage: 51.1%

![image](https://user-images.githubusercontent.com/92827264/160321083-bbfe01b8-2d64-4cab-8de4-6749d5c95b8b.png)

5 Star non-vine review percentage: 38.7%

![image](https://user-images.githubusercontent.com/92827264/160321131-d56e108b-369a-499e-b634-9ae7be3eb814.png)


## Summary

I do believe that there is a positivity bias. People that are in the vine program are usually people that are more well known for doing product reviews and when people watch a review by them they will likely rate the video higher than non-vine users. This is pretty apparent in the images below.

![image](https://user-images.githubusercontent.com/92827264/160322711-1a4c7dc3-660c-4a37-86f5-4bfc1648a5f5.png)
![image](https://user-images.githubusercontent.com/92827264/160322727-2a231d42-42d1-43a9-97ba-f59a64190ea4.png)

If you look at the number of 1 star votes from paid to unpaid it is drastic difference. Vine program has most votes in 5-3 star range where non-vine has most of the votes in 5 and 1 stars. This is most likely 
