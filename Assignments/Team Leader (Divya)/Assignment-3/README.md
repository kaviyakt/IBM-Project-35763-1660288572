

Create a `.env` file and type down the important credentials for IBM Bucket.

It would look like this:

```python
COS_ENDPOINT="s3.tok.ap.cloud-object-storage.appdomain.cloud"
COS_API_KEY_ID="fHg6fiAoBeU97es0G2i5i13lwbtMS1MAOJ1Taqw0zc1k"
COS_INSTANCE_CRN="crn:v1:bluemix:public:sql-query:us-south:a/c3e05f7492e346f390ab00aa069e5326:170bed1c-aed0-4f63-9cd4-248434e4e32e::"
```

Don't worry, this is not the real credentials of mine, just placeholders ;)

You can find these credentials under your IBM Cloud Storage Bucket Service Credentials. 
If you can't find them then you have to create the Service Credentials first. 
Also make sure to give public access to the objects inside your Bucket.

Place the `.env` file in the root folder and you're good to go.
