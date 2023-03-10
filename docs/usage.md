# Usage

Go to the path ```./Files/PDFs/``` and place the articles you want to analyze, only a maximum of 10 files can be analyzed.

## Using Docker

With docker installed and running, go to the root path of the project and execute:
```
docker compose up
```
It is going to take some minutes to analyze all files. 

Once it finish, execute the command below to delete all the containers.
```
docker compose down
```

All output files are going to be store in ```./Files/output/```.

## Using Conda

Activate ```iaop``` environment:
```
conda activate iaop
```
Execute the code with python:
```
python getInfoTEI.py
```
It is going to take some minutes to analyze all files. 

All output files are going to be store in ```./Files/output/```.

## Other
Execute the code with python:
```
python getInfoTEI.py
```
It is going to take some minutes to analyze all files. 

All output files are going to be store in ```./Files/output/```.

**Note:** This program uses two versions of GROBID, one in the cloud and the other in Docker as a backup, so if the cloud version is not available, the program won't do it either, since the backup is not running.