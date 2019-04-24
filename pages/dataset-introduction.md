# Dataset introduction

The [Home Positive Airway Pressure (HomePAP) dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing. Changes and updates to the source data and variable definitions have been coordinated in the [homepap-data-dictionary repository](https://github.com/nsrr/homepap-data-dictionary).

**Disclaimer:** These data are not perfect. Please [submit issues](https://github.com/nsrr/homepap-data-dictionary/issues) or [write on the Forum](https://sleepdata.org/forum) for any problematic findings.

## Structure of the dataset

The HomePAP dataset is broken down into three (3) files that correspond to the main study visit encounters.

1. `baseline` (Baseline) - 373 records, i.e. randomized subjects
2. `month1` (Month 1 follow-up) - 152 subjects with data
3. `month3` (Month 3 follow-up) - 140 subjects with data

The follow-up datasets also contain 373 records, though data will be missing for subjects who did not complete these visits.

## Key variables

Commonly used variables from the HomePAP dataset are listed below. [Click here to browse all dataset variables](https://sleepdata.org/datasets/homepap/variables/).

| Name                                                                             | Label                                                      |
| -------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| [**nsrrid**](https://sleepdata.org/datasets/homepap/variables/nsrrid)            | NSRR Subject Identifier                                    |
| [**clusterid**](https://sleepdata.org/datasets/homepap/variables/clusterid)      | Recoded Site Identifier                                    |
| [**age**](https://sleepdata.org/datasets/homepap/variables/age)                  | Age at baseline visit                                      |
| [**gender**](https://sleepdata.org/datasets/homepap/variables/gender)            | Gender                                                     |
| [**race3**](https://sleepdata.org/datasets/homepap/variables/race3)              | Race                                                       |
| [**treatmentarm**](https://sleepdata.org/datasets/homepap/variables/treatmentarm)| Treatment arm (i.e. initial diagnostic study type pathway) |
| [**ahi**](https://sleepdata.org/datasets/homepap/variables/ahi)                  | Final Apnea-Hypopnea Index (AHI)                           |
| [**avgpapuse**](https://sleepdata.org/datasets/homepap/variables/avgpapuse)      | Average CPAP use per night                                 |

## Data collection forms

The NSRR provides [original data collection forms as PDFs](:files_path:/forms). Many [variables link to these forms](:datasets_path:/heartbeat/variables) to give users a better idea about the origins of the underlying data.

The forms are included here for historical purposes only and are not intended for use in prospective studies. If you wish to use these forms, please check existing copyrights and regulations beforehand.

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
