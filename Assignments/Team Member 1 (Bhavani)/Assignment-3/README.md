

Create a `.env` file and type down the important credentials for IBM Bucket.

It would look like this:

```python
COS_ENDPOINT="s3.tok.ap.cloud-object-storage.appdomain.cloud"
COS_API_KEY_ID="YRStlsBXbBJcnGYn9xmbGhBB2ooFqzLtW_yWJynHlYB1"
COS_INSTANCE_CRN="crn:v1:bluemix:public:sql-query:us-south:a/4593fb0faf4a4c229846e97c313129df:04b36e4b-f535-4133-920e-439bd62b5644::"
```

Don't worry, this is not the real credentials of mine, just placeholders ;)

You can find these credentials under your IBM Cloud Storage Bucket Service Credentials. 
If you can't find them then you have to create the Service Credentials first. 
Also make sure to give public access to the objects inside your Bucket.

Place the `.env` file in the root folder and you're good to go.
