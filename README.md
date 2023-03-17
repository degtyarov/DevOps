# DevOps
test fot testing 
This section builds on the information covered in Getting started with Pipeline and introduces more useful steps, common patterns, and demonstrates some non-trivial Jenkinsfile examples.

Creating a Jenkinsfile, which is checked into source control [1], provides a number of immediate benefits:

Code review/iteration on the Pipeline

Audit trail for the Pipeline

Single source of truth [2] for the Pipeline, which can be viewed and edited by multiple members of the project.

Pipeline supports two syntaxes, Declarative (introduced in Pipeline 2.5) and Scripted Pipeline. Both of which support building continuous delivery pipelines. Both may be used to define a Pipeline in either the web UI or with a Jenkinsfile, though it’s generally considered a best practice to create a Jenkinsfile and check the file into the source control repository.
