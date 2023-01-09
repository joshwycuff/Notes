- di-terraform / python lambda update
	- Make update optional
	- Only update/install main dependencies
	- Maybe switch from virtualenv to venv
	- Maybe remove poetry dependency on poetry.lock
- cnn-aws-utils v1
	- Make boto3 an optional dependency
	- Remove custom boto3 session handling
- content manager
	- Remove temp_capture after done
	- At some point, re-think expiration lifecycle rules

Ask Jon if new dbt roles can resize warehouses.