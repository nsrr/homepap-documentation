## Montage and sampling rate information

The settings below represent the standards set at the beginning of the project. There may be a small proportion of studies and signals that do not match these standards exactly. Please review the settings at the individual sleep study level as you proceed with any analyses.

### Lab studies

| Channel               | EDF Label                  | Input 1     | Input 2 | Sampling rate (Hz)           | Hardware filters (Hz) | Sensor type                       |
|:---------------------:|:--------------------------:|:-----------:|:-------:|:----------------------------:|:---------------------:|:---------------------------------:|
| REF                   | -                          | Fpz         | -       | 200                          | -                     | Gold cup                          |
| Ground                | -                          | -           | -       | 200                          | -                     | Gold cup                          |
| Left EOG              | E1                         | E1          | Fpz     | 200                          | -                     | Gold cup or Ag/AgCl patch         |
| Right EOG             | E2                         | E2          | Fpz     | 200                          | -                     | Gold cup or Ag/AgCl patch         |
| Left Frontal EEG      | F3                         | F3          | Fpz     | 200                          | -                     | Gold cup                          |
| Right Frontal EEG     | F4                         | F4          | Fpz     | 200                          | -                     | Gold cup                          |
| Left Central EEG      | C3                         | C3          | Fpz     | 200                          | -                     | Gold cup                          |
| Right Central EEG     | C4                         | C4          | Fpz     | 200                          | -                     | Gold cup                          |
| Left Occipital EEG    | O1                         | O1          | Fpz     | 200                          | -                     | Gold cup                          |
| Right Occipital EEG   | O2                         | O2          | Fpz     | 200                          | -                     | Gold cup                          |
| Left Mastoid EEG      | M1                         | M1          | Fpz     | 200                          | -                     | Gold cup                          |
| Right Mastoid EEG     | M2                         | M2          | Fpz     | 200                          | -                     | Gold cup                          |
| ECG1                  | ECG1                       | ECG1        | Fpz     | 250                          | -                     | Gold cup or Ag/AgCl patch         |
| ECG2                  | ECG2                       | ECG2        | Fpz     | 250                          | -                     | Gold cup or Ag/AgCl patch         |
| ECG3                  | ECG3                       | ECG3        | Fpz     | 250                          | -                     | Gold cup or Ag/AgCl patch         |
| Center Chin EMG       | Cchin                      | Cchin       | Fpz     | 200                          | -                     | Gold cup or Ag/AgCl patch         |
| Left Submentalis EMG  | Lchin                      | Lchin       | Fpz     | 200                          | -                     | Gold cup or Ag/AgCl patch         |
| Right Submentalis EMG | Rchin                      | Rchin       | Fpz     | 200                          | -                     | Gold cup or Ag/AgCl patch         |
| Pulse                 | Pulse                      | Pulse       | -       |                              | -                     | Variable by site                  |
| Plethysmography       | Pleth                      | Pleth       | -       | 10 or highest allowable rate | -                     | Variable by site                  |
| Left Leg EMG          | LLeg                       | LLeg        | Fpz     | 200                          | -                     | Gold cup or Ag/AgCl patch         |
| Right Leg EMG         | RLeg                       | RLeg        | Fpz     | 200                          | -                     | Gold cup or Ag/AgCl patch         |
| Snore                 | Snore (not required)       | Snore       | -       | 200                          | -                     | -                                 |
| Thermistor            | Airflow                    | Airflow     | -       | 32                           | -                     | Variable by site                  |
| Nasal Pressure        | CannulaFlow                | CannulaFlow | -       | 128                          | -                     | Variable by site                  |
| Sum                   | Sum                        | Sum         | -       | 32                           | -                     | Variable by site                  |
| Thorax                | Chest                      | Chest       | -       | 32                           | -                     | Variable by site                  |
| Abdomen               | Abd                        | Abd         | -       | 32                           | -                     | Variable by site                  |
| XFlow                 | XFlow (not always present) | Xflow       | -       | 32                           | -                     | Derived from Embla XactTrace belt |
| SpO2                  | SAO2                       | SAO2        | -       | 10 or highest allowable rate | -                     | Variable by site                  |
| Leak                  | Leak                       | Leak        | -       | 1                            | -                     | Variable by site                  |
| Position              | Position                   | Position    | -       | 10-Jan                       | -                     | Variable by site                  |
| CPAP Flow             | MaskFlow                   | MaskFlow    | -       | 32                           | -                     | Variable by site                  |

Note: All EOG, EEG signals were to be collected to reference. This was not done for all clusterids, see [known issues list](:pages_path:/polysomnography-introduction.md) for more details. When possible, Chin EMG, Leg EMG and ECG signals will be collected to reference.  This was not done for all clusterids, see [known issues list](:pages_path:/polysomnography-introduction.md) for more details.

Signals will be collected unfiltered (at hardware settings). This may vary according to the acquisition system.

Not all clusterids meet the minimum sampling rates, see [known issues list](:pages_path:/polysomnography-introduction.md) for more details.

### Home studies

|  Channel      |   Minimum Sampling Rate (Hz) (may be exceeded)  |
|:--------------|:------------------------------------------------|
| Nasal         | 20                                              |
| EKG           | 200                                             |
| Thermistor    | 10                                              |
| Thorax        | 10                                              |
| Abdomen       | 10                                              |
| Gravity X     | 10                                              |
| Gravity Y     | 10                                              |
| Battery       | 2                                               |
| Snore         | 10                                              |
| SpO2          | 3                                               |
| SpO2-BB       | 3                                               |
| Pulse         | 3                                               |
| RD-Pleth      | 75                                              |
| SpO2-quality  | 3                                               |
| RD-Quality    | 75                                              |
| Flow          | 20                                              |
| Activity      | 10                                              |
| Elevation     | 10                                              |
| Position      | 10                                              |
| Phase         | 10                                              |
| RMI           | 10                                              |
| RR            | 1                                               |
| XSum          | 10                                              |
| Tidal Volume  | 10                                              |
| XFlow_PDS     | 10                                              |
| Flattening    | 50                                              |

No hardware filters were applied.
