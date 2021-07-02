# Notebooks
Collections of Jupiter notebooks


## Launching Jupyter via docker
Run
```
 docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan/work jupyter/datascience-notebook:33add21fab64
 ```