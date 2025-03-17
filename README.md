# Formant-analysis-of-Dysarthria-speakers
#### Authors: Rida Ahmed, Monowar Hossain, and Oskari Laakkonen

## Overview
This project extracts vowel formants (F1 and F2) from labeled speech segments using Praat. It includes:
- A Praat script for automated formant extraction.
- Resultant data files (`JFresult.txt`, `BKresult.txt`, `BBresult.txt`).
- Cropped sound files (in `/sounds`).

## Usage
1. **Praat Script** (`scripts/extract_formants.praat`):  
   - **Input**: Directory containing `.WAV` files and corresponding `.TextGrid` files.  
   - **Output**: Formant data (F1, F2) saved to a text file.  
   - Adjust `input_directory` and `Result_file` paths in the script before running.

2. **Data Files**  
   Results are stored in `/data` for reference.

## Data Structure
- `/sounds`: Cropped audio files (WAV format).  
- `/data`: Output files with formant values.  
- `/scripts`: Contains the Praat script.

## Citation
- The Praat script is adapted from Mietta Lennes’s original work:  
  [Praat Script for Pitch Data Collection](https://lennes.github.io/spect/scripts/collect_pitch_data_from_files.praat).  
- Please cite this repository if you use our code or data.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
