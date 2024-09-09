### Getting Started

## Create a virtual environment if you don't have one

In this example we use CONDA.

```
conda create --name language-service
```

if you want to see if the new environment is present use

```
conda env list
```

activate the new environment

```
conda activate language-service
```

install the requests package

```
conda install requests
```

Run the script to translate the Google Sheet to JSON

```
python csv_to_vanilla_i18n.py 1ouSogLBySSER3bi8pEuHVdi3-ODx-K1GzYSIp57EmmU
```

You will find the results in ... forestmonitoring_language_service/vanilla-i18n

## Where are the translations stored?

The translations you will find in this google sheet:
https://docs.google.com/spreadsheets/d/1ouSogLBySSER3bi8pEuHVdi3-ODx-K1GzYSIp57EmmU/edit?gid=0#gid=0

## Deactivate the virtual environment

When you are finished, you can deactivate the virtual environment.

```
conda deactivate
```
