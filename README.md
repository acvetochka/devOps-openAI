
| NAME                   | PROMPT                                    | DESCRIPTION                                                               | EXAMPLE      |
|------------------------|-------------------------------------------|---------------------------------------------------------------------------|--------------|
| app.yaml               | Create Application Config                 | YAML to define the basic schema of a Kubernetes application              | [app.yaml](yaml/app.yaml)|
| app-livenessProbe.yaml | Add Liveness Probe                        | YAML to add a livenessProbe to a container to check if it is functioning  |[app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)|
| app-readinessProbe.yaml| Add Readiness Probe                       | YAML to add a readinessProbe to a container to ensure it is ready to receive traffic |[app-readinessProbe.yaml](yaml/app-readinessProbe.yamll)|
| app-volumeMounts.yaml  | Configure Volume Mounts                   | YAML to configure volumeMounts for a container that uses specific files or directories |[app-volumeMounts.yaml](yaml/app-volumeMounts.yaml)|
| app-cronjob.yaml       | Create CronJob                            | YAML to create a manifest for running a task on a regular basis using CronJob |[app-cronjob.yaml](yaml/app-cronjob.yaml)|
| app-job.yaml           | Create Job                                | YAML to create a manifest for running a one-off task                      |[app-job.yaml ](yaml/app-job.yaml)|
| app-multicontainer.yaml| Create Multi-container Application       | YAML to create a manifest for deploying an application that contains multiple containers |[app-multicontainer.yaml](yaml/app-multicontainer.yaml)|
| app-resources.yaml     | Configure Resource Limits                | YAML to configure resources (CPU and memory size) for your application's container |[app-resources.yaml](yaml/app-resources.yaml)|
| app-secret-env.yaml    | Add Secrets or Environment Variables     | YAML to add confidential data or environment variables to a container using secrets |[app-secret-env.yaml](yaml/app-secret-env.yaml)|