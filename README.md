# jupyter-sql
Jupyter pyspark-notebook image with python3 and mysql client

## Clone Repo
`git clone git@github.com:mathcunha/jupyter-sql.git`


## Build image
`docker build -t jupyter-sql .`


## Run image

Replace Workdir with absolute BI_python folder path and run :
`docker run -it -p 8888:8888 -v WORKDIR:/home/jovyan/work jupyter-sql`

Option : `--NotebookApp.token=TOKEN_TO_REPLACE`
