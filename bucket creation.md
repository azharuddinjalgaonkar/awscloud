To create a bucket

Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/.

Choose Create bucket.

The Create bucket page opens.

In Bucket name, enter a DNS-compliant name for your bucket.

The bucket name must:

Be unique across all of Amazon S3.

Be between 3 and 63 characters long.

Not contain uppercase characters.

Start with a lowercase letter or number.

After you create the bucket, you can't change its name. 

Important
Avoid including sensitive information, such as account numbers, in the bucket name. The bucket name is visible in the URLs that point to the objects in the bucket.

In Region, choose the AWS Region where you want the bucket to reside.

Choose a Region close to you to minimize latency and costs and address regulatory requirements. Objects stored in a Region never leave that Region unless you explicitly transfer them to another Region. For a list of Amazon S3 AWS Regions, see AWS Service Endpoints in the Amazon Web Services General Reference.

In Bucket settings for Block Public Access, keep the values set to the defaults.

By default Amazon S3 blocks all public access to your buckets. We recommend that you leave all Block Public Access settings enabled. For more information about blocking public access, see Using Amazon S3 Block Public Access in the Amazon Simple Storage Service Developer Guide.

Choose Create bucket.

You've created a bucket in Amazon S3....


@@@ Uploading an object to a bucket:

Now that you've created a bucket, you're ready to upload an object to it. An object can be any kind of file: a text file, a photo, a video, and so on.

To upload an object to a bucket

In the Bucket list, choose the name of the bucket that you want to upload your object to.

On the Overview tab for your bucket, choose Upload or Get Started.

To choose the file to upload, in the Upload dialog box, choose Add files.

Choose a file to upload, and then choose Open.

Choose Upload.

You've successfully uploaded an object to your bucket.







