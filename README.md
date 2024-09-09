# Getting Started

## 1. Create a virtual environment if you don't have one

In this example we use CONDA.

```
conda create --name language-service
```

if you want to see if the new environment is present.

```
conda env list
```

activate the new environment.

```
conda activate language-service
```

install the requests package.

```
conda install requests
```

## What do I have to do to update the translations?

Run the following command to translate the Google Sheet to JSON.

```
python csv_to_vanilla_i18n.py 1ouSogLBySSER3bi8pEuHVdi3-ODx-K1GzYSIp57EmmU
```

You will find the results in the /vanilla-i18n folder.

## Where are the translations stored?

The translations are stored in this google sheet:
https://docs.google.com/spreadsheets/d/1ouSogLBySSER3bi8pEuHVdi3-ODx-K1GzYSIp57EmmU/edit?gid=0#gid=0

## Deactivate the virtual environment

To deactivate the virtual environment.

```
conda deactivate
```
