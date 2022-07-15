# save_logs_to_s3
## Export AWS logs to S3
This repository contains a program for saving logs in S3
### Save options
In params.py specify the following parameters:
- Initialization parameters in S3: Access_Key_ID, Secret_access_key
- Parameters for saving log files:
    - 'date_format' is the date format in the file name
    - 'folder_name_ec2' is the name of the folder where the log files are located
    - 'folder_name_s3' is the name of the folder in s3 to which logs will be saved
    - 'bucket_name' is the bucket name in s3
    
### Saving files to s3
To save log files to s3, run the program run_save_logs.py
