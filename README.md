Use ipython notebook to run.
probably good to run by a docker with following commands.

```
docker pull joemphilips/datascience
docker run -it -v $(pwd)/notes:/home/jovyan/work joemphilips/datascience start-notebook.sh
```
