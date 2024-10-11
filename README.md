<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## WRLD-SMB Dataset

WRLD-SMB is an open audio dataset featuring a collection of synthetic drum recordings in the style of Brazilian samba music. It includes 1,100 audio loops recorded in uncompressed stereo WAV format, along with paired JSON files intended for the supervised training of generative AI audio models.

## Overview

This dataset was developed using multi-velocity audio samples and a paired MIDI dataset. The intended use of this dataset is to train or fine-tune AI models in learning high-performance drum notations, aiming to replicate the live sound of a small drum ensemble. To facilitate augmentation and supervised training with labeled audio data, a dropout technique was employed on the rendered audio files to generate variational mixes of the drum tracks.

The primary purpose of this dataset is to provide accessible content for machine learning applications in music and audio. Potential use cases include generative music, feature extraction, tempo detection, audio classification, rhythm analysis, drum synthesis, music information retrieval (MIR), sound design and signal processing.

**Specifications**

- 1,100 audio loops (approximately 5.5 hours)
- 16-bit 44.1kHz WAV format
- Tempo range: 90–120 BPM
- Paired label data (WAV + JSON)
- Variational drum patterns
- Subgenre styles (Traditional and modern samba, bossa nova, fusion)

## Examples

See examples folder to preview mp3 demos.


## License

This dataset is developed by WaivOps, a crowdsourced music project managed by sound label company Patchbanks. All recordings have been compiled by verified sources for copyright clearance.

The WRLD-SMB dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
## Download

Direct WAV Download (3.1GB) [wrld_smb_drm_8br_id_001_wav](https://zenodo.org/records/13921290/files/wrld_smb_drm_8br_id_001_wav.tar.gz?download=1)

Direct JSON Download (39.7KB) [wrld_smb_drm_8br_id_001_json](https://zenodo.org/records/13921290/files/wrld_smb_drm_8br_id_001_json.tar.gz?download=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13921290.svg)](https://doi.org/10.5281/zenodo.13921290)
## File Name Reference

| **Label**             | **Reference**                                                  |
| ----------------- | ------------------------------------------------------------------ |
| bpm  | The tempo of the audio file|
| wrld | Main genre (world)|
| smb | Subgenre (samba)|
| drm | Instrument (drums)|
| id | Identification number|
| 0000 | Playlist track number|

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@misc{WRLD-SMB,
author = {WaivOps},
title = {WaivOps WRLD-SMB: Open Audio Resources for Machine Learning in Music},
year = {2024},
doi = {10.5281/zenodo.13921290},
url = {https://doi.org/10.5281/zenodo.13921290},
}
```
## Additional Info

For any questions or feedback please email info@patchbanks.com.
