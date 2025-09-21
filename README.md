# KUBERNETES: WRITE YOUR FIRST CUSTOM HELM CHART FROM SCRATCH
---
>Goal: 
- This document was created to showcase how we can develop a custom HELM chart to build an application.
- I will keep updating this document until we're done with the video series
---
>Do you want to practice along? Link to my Youtube channel playlist [here](https://www.youtube.com/playlist?list=PLX8Ra2KD8-kGbYpqPOfEb84houTkiazUr)

## Pre-requisites:
- An OS of your choice (I am using `Rocky Linux 10`)
- A `Kubernetes cluster` up and running (Minikube, kind, k3s or any)
- `Kubectl` to interact with the cluster api server
- `Helm` command line tool
- Good knowledge of `Kubernetes`

## Folder structure
```sh
monlabolinux/ --> Root folder of the helm chart
├── Chart.yaml --> Chart information
├── files --> Will be useful for video 06 of the video series
│   └── index.html
├── README.md --> "What you're actually learning"
├── templates --> Kubernetes templatized files and NOTES.txt
│   ├── configmaps.yaml
│   ├── deployment.yaml
│   ├── NOTES.txt
│   └── service.yaml
└── values.yaml --> Values to your templatized files

3 directories, 8 files
```
### Happy Learning 🚀