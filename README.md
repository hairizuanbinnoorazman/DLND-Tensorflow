# DLND-Tensorflow
Learning Tensorflow via the Deep Learning Course

# Accessing the project

Instead of accessing the project on local computers or virtual machines, access it via the Docker container environment.
The set of instructions below assume that the user already installed docker in their local environments.

**Setting up the docker image**

```
docker pull continuumio/anaconda3
docker run -it -p 8888:8888 -p 8889:8889 continuumio/anaconda3 /bin/bash
```

**Run Jupyter notebook**

```
git clone <this repo>
jupter notebook --ip=0.0.0.0
```
