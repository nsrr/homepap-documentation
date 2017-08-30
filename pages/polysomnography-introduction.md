# Polysomnography introduction

The HomePAP project includes lab-based and home-based polysomnography. Those randomized to the laboratory-based pathway underwent attended overnight PSG in an accredited sleep laboratory, followed by a second attended overnight PSG for titration with CPAP. If the apnea-hypopnea index (AHI) was ≥ 15 during the first two hours of the initial PSG, the patient proceeded with CPAP titration in the same night, termed a "split-night" study. Those randomized to the home-based pathway were given a portable limited-channel sleep monitoring device (EmblettaX-30, Embla Inc., Broomfield, CO, USA) which was taken home. These patients received standardized in-person training on how to apply the monitoring device on at night by personnel affiliated with each accredited sleep center, and technicians were available overnight by phone to answer any questions.

Notes:

- Montage and Sampling Rate Information (*coming soon*)
- [HomePAP PSG Scoring Manual (PDF)](:files_path:/documentation?f=HomePAP_PSG_Scoring_Manual.pdf)

## Signal and annotation files

[Raw polysomnography data](:files_path:/polysomnography) are available for 343 subjects. Each recording has a signal file (.EDF) and at least one version of the event scoring and epoch staging annotations (.XML).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from RemLogic (home-based) and Compumedics Profusion (lab-based).
2. **[XML (Profusion)](:files_path:/polysomnography/annotations-events-profusion)** - Annotation files exported from Compumedics Profusion. ([Learn more...](https://github.com/nsrr/edf-editor-translator/wiki/Compumedics-Annotation-Format))
3. **[XML (NSRR)](:files_path:/polysomnography/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://www.sleepdata.org/community/tools/12) tool.

NSRR XML files can be overlaid onto EDF signal files using the [EDF Viewer tool](https://sleepdata.org/community/tools/nsrr-edf-viewer). For more information about the XML translation (mapping) process, review the files available on the [EDF Editor and Translator Releases page](https://github.com/nsrr/edf-editor-translator/releases).

## Known issues

- <note discrepancies in file counts>

## History / changelog

*September 2017*
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion and RemLogic

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
