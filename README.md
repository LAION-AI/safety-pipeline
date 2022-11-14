# LAION safety pipeline

## Introduction
Using a common pipeline to process image and text data and create an output file with the safety scores.

## Usage

1. Clone repository
2. Run once using the **main.py** file to download all models and check single-node usage
3. Configure dd.sh
4. Run multi-node script with the following command

```
sbash dd.sh
```