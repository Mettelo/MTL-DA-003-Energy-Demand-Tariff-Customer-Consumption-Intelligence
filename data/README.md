# Data Workspace — MTL-DA-003

## Dataset

**SmartMeter Energy Consumption Data in London Households**  
Publisher: UK Power Networks  
Source: London Datastore

The dataset contains half-hourly electricity consumption readings for 5,567 London households participating in the Low Carbon London project between November 2011 and February 2014.

The complete CSV data expands to roughly 10 GB and around 167 million rows.

## Official Source

https://data.london.gov.uk/dataset/smartmeter-energy-consumption-data-in-london-households-vqm0d

## Available Files

The London Datastore provides:

- a large ZIP containing the full dataset;
- a split ZIP containing 168 CSV files of roughly one million rows each;
- a tariff file covering the dynamic time-of-use trial.

For team delivery, the **168-file split version is recommended** because it is easier to process incrementally and supports realistic data-ingestion work.

## Licence

Creative Commons Attribution.

Teams must retain dataset attribution in their repositories and final documentation.

## Folder Structure

```text
data/
├── README.md
├── raw/
├── reference/
└── metadata/
```

## raw/

Do **not** commit the full extracted dataset into this master GitHub repository.

The source is very large.

Use this folder for:
- small approved extracts;
- file manifests;
- checksums;
- download instructions;
- sample files where appropriate.

Each team should download the raw source directly from the official source and configure its own local/cloud processing environment.

## reference/

Store:
- tariff reference files;
- source documentation;
- licence notes;
- field interpretation notes.

## metadata/

Store:
- provenance;
- file inventory;
- schema;
- data dictionary;
- known limitations;
- ingestion notes.

## Team Repository Data Structure

Each team should use:

```text
data/
├── README.md
├── raw/         # usually gitignored because of file size
└── processed/   # only small/reasonable derived artefacts
```

The team's `data/README.md` must explain exactly how a reviewer obtains and prepares the raw data.
