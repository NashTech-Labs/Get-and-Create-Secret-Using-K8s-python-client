#### Python client for the kubernetes API for Secret:

`KubeConfig:` to pass the config on local cluster e.g minikube we use below command: 

`config. load_kube_config()`

`configuration.api_key = {"authorization": "Bearer" + bearer_token}` 

I've used Bearer Token which enable requests to authenticate using an access key.

### Get secrets using Kubernetes Python client:

Call the function get_secrets(cluster_details,"default") in your code for listing.

And run following command:

`python3 get_create.py`

### Create secrets using Kubernetes Python client:

call the function create_secret(cluster_details,"default") for creating a secret in your cluster.

And run following command:

`python3 get_create.py`

Now, you can verify the secret by listing it using the code and calling get function.