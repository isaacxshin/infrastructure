# Devops Code Challenge

 
Overview of the script: 

It will first list the buckets you have in your S3 with the creation date and the owner ID. 

The second command shows the total number of files in the bucket - we can use this --query to filter based on requirements 

The third command shows the Region and the storage type for each file in the bucket

The fourth command shows Total size of the files, Last modified dates, and the size results in KB and MB

# HOW TO START

In this example the bucketname is testgpc, you can also specify a specific folder as well 

EXAMPLE $ ./gpcscript testgpc

EXAMPLE FOLDER  $ ./gpcscript testgpc/folder1
