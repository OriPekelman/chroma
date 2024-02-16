# Usage

well, deploy the app to Upsun.com
```
import chromadb
client = chromadb.HttpClient(host='main-bvxea6i-7yfoa6rnmrjuq.eu-3.platformsh.site', port=443,  ssl = True)
collection = client.get_or_create_collection("test")
```
make sure to update the host URL and set port to 443 and ssl to True
