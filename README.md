# veld_chain__train_spacy_apis_ner

This repo contains [chain velds](https://zenodo.org/records/13322913) encapsulating a spacy NER
training setup on APIS data.

## requirements

- git
- docker compose (note: older docker compose versions require running `docker-compose` instead of 
  `docker compose`)

Clone this repo with all its submodules
```
git clone --recurse-submodules https://github.com/veldhub/veld_chain__train_spacy_apis_ner.git
```

## how to reproduce

The following chain velds were used. Open the respective veld yaml file for more information.

**[./veld_convert.yaml](./veld_convert.yaml)** 

XX

```
docker compose -f veld_convert.yaml up
```

**[./veld_create_config.yaml](./veld_create_config.yaml)** 

XX

```
docker compose -f veld_create_config.yaml up
```

**[./veld_train.yaml](./veld_train.yaml)** 

XX

```
docker compose -f veld_train.yaml up
```

**[./veld_analysis.yaml](./veld_analysis.yaml)** 

XX

```
docker compose -f veld_analysis.yaml up
```

**[./veld_publish_to_hf.yaml](./veld_publish_to_hf.yaml)** 

XX

```
docker compose -f veld_publish_to_hf.yaml up
```
