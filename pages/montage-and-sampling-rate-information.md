## Montage and sampling rate information

The settings below represent the standards set at the beginning of the project. There may be a small proportion of studies and signals that do not match these standards exactly. Please review the settings at the individual sleep study level as you proceed with any analyses.

### Lab studies

|  Channel                    |   Channel Derivation  |  Sampling Rate (Hz)           |  Sensor Type                |
|:---------------------------:|:---------------------:|:-----------------------------:|:---------------------------:|
| REF                         |                       | 200                           | Gold cup                    |
| Ground                      |                       | 200                           | Gold cup                    |
| E1                          | E1-REF (FPz)          | 200                           | Gold cup or Ag/AgCl patch   |
| E2                          | E2-REF (FPz)          | 200                           | Gold cup or Ag/AgCl patch   |
| Chin                        | Lchin-Cchin           | 200                           | Gold cup or Ag/AgCl patch   |
| F4                          | F4-M1                 | 200                           | Gold cup                    |
| C4                          | C4-M1                 | 200                           | Gold cup                    |
| O2                          | O2-M1                 | 200                           | Gold cup                    |
| F3                          | F3-M2                 | 200                           | Gold cup                    |
| C3                          | C3-M2                 | 200                           | Gold cup                    |
| O1                          | O1-M2                 | 200                           | Gold cup                    |
| ECG                         | ECG3-ECG1             | 250                           | Gold cup or Ag/AgCl patch   |
| Pulse                       |                       |                               | Variable by site            |
| Pleth                       |                       | 10 or highest allowable rate  | Variable by site            |
| LLeg                        | LLeg1-LLeg2           | 200                           | Gold cup or Ag/AgCl patch   |
| RLeg                        | RLeg1-RLeg2           | 200                           | Gold cup or Ag/AgCl patch   |
| Snore (not required)        |                       | 200                           |                             |
| Airflow                     |                       | 32                            | Variable by site            |
| CannulaFlow                 |                       | 128                           | Variable by site            |
| Sum                         |                       | 32                            | Variable by site            |
| Chest                       |                       | 32                            | Variable by site            |
| Abd                         |                       | 32                            | Variable by site            |
| XFlow (not always present)  |                       | 32                            | Variable by site            |
| SAO2                        |                       | 10 or highest allowable rate  | Variable by site            |
| Leak                        |                       | 1                             | Variable by site            |
| Position                    |                       | 1-10                          | Variable by site            |
| MaskFlow                    |                       | 32                            | Variable by site            |

Note: All EOG, EEG signals were to be collected to reference. This was not done for all clusterids, see [known issues list](:pages_path:/polysomnography-introduction.md) for more details. When possible, Chin EMG, Leg EMG and ECG signals will be collected to reference.  This was not done for all clusterids, see [known issues list](:pages_path:/polysomnography-introduction.md) for more details.

Signals will be collected unfiltered (at hardware settings). This may vary according to the acquisition system.

Not all clusterids meet the minimum sampling rates, see [known issues list](:pages_path:/polysomnography-introduction.md) for more details.
