
| NAME                   | PROMPT                                    | DESCRIPTION                                                               | EXAMPLE      |
|------------------------|-------------------------------------------|---------------------------------------------------------------------------|--------------|
| app               | Create manifest for deploying an application consisting of a single container              | YAML to define the basic schema of a Kubernetes application              | [app.yaml](yaml/app.yaml)|
| app-livenessProbe | Add a livenessProbe to the container to check if it is functioning                    | YAML to add a livenessProbe to a container to check if it is functioning  |[app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)|
| app-readinessProbe|  Add a readinessProbe to the container to ensure it is ready to receive traffic                    | YAML to add a readinessProbe to a container to ensure it is ready to receive traffic |[app-readinessProbe.yaml](yaml/app-readinessProbe.yamll)|
| app-volumeMounts  | Configure volumeMounts for the container that uses specific files or directories                  | YAML to configure volumeMounts for a container that uses specific files or directories |[app-volumeMounts.yaml](yaml/app-volumeMounts.yaml)|
| app-cronjob      | Create a manifest to run a task regularly using a CronJob                           | YAML to create a manifest for running a task on a regular basis using CronJob |[app-cronjob.yaml](yaml/app-cronjob.yaml)|
| app-job           | Create a manifest to run a one-time task                             | YAML to create a manifest for running a one-off task                      |[app-job.yaml ](yaml/app-job.yaml)|
| app-multicontainer| Create a manifest for deploying an application that contains multiple containers      | YAML to create a manifest for deploying an application that contains multiple containers |[app-multicontainer.yaml](yaml/app-multicontainer.yaml)|
| app-resources     | Configure resource limits (CPU and memory) for your application container             | YAML to configure resources (CPU and memory size) for your application's container |[app-resources.yaml](yaml/app-resources.yaml)|
| app-secret-env    | Add confidential data or environments to the container using secrets or environment variables     | YAML to add confidential data or environment variables to a container using secrets |[app-secret-env.yaml](yaml/app-secret-env.yaml)|



