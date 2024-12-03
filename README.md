# nextflow-demo

Basic demo of real world implementation of Nextflow. 

See part 2 of [our Hello Nextflow](https://sydney-informatics-hub.github.io/hello-nextflow/) training materials for guidance on how this demo was built. 

## Execution

To run with Docker: 

```
nextflow run main.nf -profile DOCKER
```

To run with Singularity on NCI Gadi: 

```
module load nextflow singularity
nextflow run main.nf -profile GADI
```