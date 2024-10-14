# MLFlow-basic-Operation

```
import dagshub
dagshub.init(repo_owner='manishkumarsahu724', repo_name='MLFlow-basic-Operation', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
```