# setup rancher-cicd
### Demo Example Pipeline
    https://github.com/rancher/pipeline-example-go
    
### Config secret > Docker Hub Registry to push image
    https://rancher.com/docs/rancher/v2.5/en/k8s-in-rancher/secrets/

### Config trigger ???

### Config Notification ???

### Config auto trigger for pipeline
    -Rancher automatically config when enable repository.
    -prerequisite: webhood github connected rancher server.
    -testing env not yet config because github can not rancher server.

### Setup Process CICD for a project
    Ref: https://rancher.com/docs/rancher/v2.5/en/pipelines/

    1. Create Project
       -organize k8s resource as : namespace, worload, ...
    2. Add a Repository for project
       -Config webhood automatically.
    
    3. Create pipeline for a project.
       -each project have only one pipeline.
       -pipeline maybe has many branchs as master(production), dev(developing),...
    4. Run pipeline.
    
    5. Enjoy result !!!
    6. Thanks !!!
