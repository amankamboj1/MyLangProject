## MyLangProject
This project was created to be a fun way of learning Chinese (Mandrain) for my daughter who is a non-native speaker.

As I also don't know how to read/write/speak Chinese, it was a good problem statement to solve at home :)

So the requirements came from my daughter, I designed some basic (but workable) UI and got approval from her.

I was able to help her listen to text she received in homework and get the meaning of the words.

# Details
The project is hosted on S3 bucket in AWS.

The feedback form redirects input to lambda which uses SES to send email to an account to collect the feedback.

It can be accessed directly via S3 hosting URL: http://aryaislearner.com.s3-website-ap-southeast-1.amazonaws.com/
