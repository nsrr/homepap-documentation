# Polysomnography introduction

The HomePAP project includes lab-based and home-based polysomnography. Those randomized to the laboratory-based pathway underwent attended overnight PSG in an accredited sleep laboratory, followed by a second attended overnight PSG for titration with CPAP. If the apnea-hypopnea index (AHI) was ≥ 15 during the first two hours of the initial PSG, the patient proceeded with CPAP titration in the same night, termed a "split-night" study. Those randomized to the home-based pathway were given a portable limited-channel sleep monitoring device (EmblettaX-30, Embla Inc., Broomfield, CO, USA) which was taken home. These patients received standardized in-person training on how to apply the monitoring device at night by personnel affiliated with each accredited sleep center, and technicians were available overnight by phone to answer any questions.

Notes:

- [Montage and Sampling Rate Information](:pages_path:/montage-and-sampling-rate-information.md)
- [HomePAP PSG Scoring Manual (PDF)](:files_path:/documentation?f=HomePAP_PSG_Scoring_Manual.pdf)
- The full-night lab PSG studies are from the initial overnight PSG (not the CPAP titration overnight)

## Signal and annotation files

[Raw polysomnography data](:files_path:/polysomnography) are available for 343 subjects. Each recording has a signal file (.EDF) and at least one version of the event scoring and epoch staging annotations (.XML).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from RemLogic (home-based) and Compumedics Profusion (lab-based).
2. **[XML (Profusion)](:files_path:/polysomnography/annotations-events-profusion)** - Annotation files exported from Compumedics Profusion (lab-based only). ([Learn more...](https://github.com/nsrr/edf-editor-translator/wiki/Compumedics-Annotation-Format))
3. **[XML (NSRR)](:files_path:/polysomnography/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://www.sleepdata.org/community/tools/12) tool. Available for both home-based and lab-based studies.

NSRR XML files can be overlaid onto EDF signal files using the [EDF Viewer tool](https://sleepdata.org/community/tools/nsrr-edf-viewer). For more information about the XML translation (mapping) process, review the files available on the [EDF Editor and Translator Releases page](https://github.com/nsrr/edf-editor-translator/releases).

## Known issues

*Home-based studies*

- Most do not have analysis stop annotations
- Some do not have analysis start nor stop annotations
- The number of respiratory events listed in the annotation XML files will not always match the variable in the CSV dataset file
- Pleth signals have a blank physical dimension
- Position, Phase, and RMI signals contain a non-ASCII character for their physical dimensions.
- Scoring data (XML annotations) are not available for three subjects (1600261, 1600324, 1600350) due to data loss

*Lab-based studies*

- Studies collected from clusterids 33 and 90 do not contain pleth or leak signals
- Studies collected from clusterid 90: the EEG, chin EMG, leg EMG, and ECG are linked signals. Some EOG signals are bipolar referenced. There is one study that the CannulaFlow signal looks like an ECG signal.  Pulse signals for this clusterid look like an ECG signal, the physical dimension is mV, not a typical physical dimension of bpm.  There is a DHR signal with a physical dimension of bpm.
- Studies collected from clusterid 46: the EOG, chin EMG, and EEG are bipolar referenced.
- Studies collected from clusterid 29: sometimes the chin EMG, EEG, and leg EMG signals are bipolar referenced. Sometimes the ECG signal is bipolar referenced.
- Studies collected from clusterid 58: some studies contain duplicate signals, for example: snore, PAP, TcCO2, EtCO2, O1, O2, and Gravity. Some studies contained two signals with similar names, for example: CHEST and CHEST1. For duplicate or similar signals, it appears sometimes the signals are identical in morphology, other times the signals appear to have one authentic signal and another signal which contains noise/artifact.
- Studies collected from clusterid 29: one study has an empty field at line 25.
- Studies collected from clusterid 46: some studies contain duplicate named signals, for example, ECG, Pulse, and TidVol. Some of these duplicate named signals appear to be the same in morphology, some do not.
- Studies collected from clusterid 58 may contain studies where the respiratory belt signals do not meet the minimum rate of 32 Hz.
- Studies collected from clusterids 35, 29, and 46 may contain studies where the CannulaFlow signal does not meet the minimum rate of 128 Hz.

## History / changelog

*September 2017*
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion and RemLogic

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
