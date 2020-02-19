# stringify-gcp-credentials
This python script stringifies a GCP service acocunt (in JSON) and makes the GCP service account suitable for ``gcs.credentials.json`` and other GCP-related connectors Confluent offers.

# how to run this script
python3 stringify-gcp-credentials.py gcp-credentials.json output.txt
