# SSM Tools

This repository contains Jupyter notebooks for creating self-similarity matrix (SSM) representations from audio and symbolic music files.


## Environment Setup

The code and notebooks in this repository are optimized for Python 3.11. We recommend setting up a virtual environment using Conda to manage the dependencies. You can create a new environment named `ssm_tools` by running:

```bash
conda create -n ssm_tools python=3.11
```
Once the environment is created and activated, install the required packages using:
```bash
pip install -r requirements.txt
```

## Repository Structure

The repository contains the following files:

- `music21_df_ssm.ipynb`: A notebook for creating SSM representations based on symbolic music inputs. It can process all formats compatible with music21, using pitch class distribution as the basis for SSM calculation.
- `music21_df_ssm_plotly.ipynb`: A version of the music21_df_ssm notebook, but with a Plotly implementation for convenient zooming and panning.
- `ssm_audio.ipynb`: A notebook for creating SSM representations based on audio files. It uses librosa for audio processing and works best with WAV files, featuring MFCC and chroma features for SSM calculation.
- `ssm_audio_plotly.ipynb`: A version of the ssm_audio.ipynb notebook, but with a Plotly implementation for convenient zooming and panning.
- `ssm_detail_vector.ipynb`: A tutorial notebook that goes into detail about how MFCC is calculated and how feature vectors are defined.

## Getting Started

To get started, clone this repository and navigate to the cloned directory. Activate your `ssm_tools` environment and install the required packages as described in the Environment Setup section above.