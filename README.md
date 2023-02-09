# Expired_Feed

Here's an example of how you could set up your script using AWS Lambda:

Create a new AWS Lambda function in your AWS account.
In the function configuration, select the appropriate runtime (e.g., Python) and provide a name for your function.
In the function code, paste your script.
Create an IAM role for your function with the necessary permissions (e.g., to access the My+ Plus Leads and Thanks.IO APIs).
Save and test your function to make sure it runs correctly.
Set up a CloudWatch Event to trigger your function on a daily basis. This can be done from the AWS Management Console, under the "Event Bridge" section. You'll need to create a rule that specifies the schedule for when the function should run (e.g., a daily cron expression such as 0 0 * * ? *).
