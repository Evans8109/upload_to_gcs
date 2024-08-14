# upload_to_gcs
need to check the env for the key

""" 

在本機設置.json的環境變數
export GOOGLE_APPLICATION_CREDENTIALS="/usr/local/key/evans-class-c67887cf1aed.json"

or 

在code裡添加
from google.cloud import storage
storage_client = storage.Client.from_service_account_json('/path/to/your/service-account-file.json')

"""
