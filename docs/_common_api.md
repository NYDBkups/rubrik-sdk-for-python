# _common_api

Internal method that consolidates the base API functions.

```py
def _common_api(call_type, api_version, api_endpoint, config=None, job_status_url=None, timeout=15, authentication=True)
```

## Arguments
call_type {str} -- The type of API call you wish to make. Valid choices are 'GET', 'POST', 'PATCH', 'DELETE', and 'JOB_STATUS'.

api_version {str} -- The version of the Rubrik CDM API to call.

api_endpoint {str} -- The endpoint (ex. cluster/me) of the Rubrik CDM API to call.


## Keyword Arguments
config {dict} -- The specified data to send with POST and PATCH API calls. (default: {None})

job_status_url {str} -- The job status URL provided by a previous API call. (default: {None})

timeout {int} -- The number of seconds to wait to establish a connection the Rubrik Cluster. (default: {15})

authentication {bool} -- Flag that specifies whether or not to utilize authentication when making the API call. (default: {True})


## Returns
dict -- The API call response.


