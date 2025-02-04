# Cosmos QA: Machine Reading Comprehension with Contextual Commonsense Reasoning (EMNLP'2019)

This repository includes the source code and data for Cosmos QA.

To run code of distilbert, few changes are necessary,
1. Import model file as modelling_distil to import BertMultiwayattention model which is same as bert
2. Download tar file for distilebert from [here](https://drive.google.com/file/d/10gLGcxPNaNorV2hF8Msr_XF4O7N8pgN5/view?usp=sharing) and set path in modelling file to run it.

## Project Page and Leaderboard

* Please refer detailed examples, resources, as well as a leaderboard in our project page: [Project Page](https://wilburone.github.io/cosmos)
* To measure the performance of your system or create a submission to our leaderboard, please refer to [Leaderboard](https://leaderboard.allenai.org/cosmosqa/submissions/public) for detailed instructions and policies.

## Repo Details

* The training/dev/test datasets for Cosmos QA can be found in ```data/```
* The BERT with multiway attention model can be ran and tuned with ```grid_search.sh```. We also released the model file that we used in our paper for BERT multiway attention model [Here](https://drive.google.com/open?id=18g8vRa_VqNvACF4BPJXQ-wmdLxWaRvNi)

## Requirements

Python3, Pytorch1.0, tqdm, boto3, requests
