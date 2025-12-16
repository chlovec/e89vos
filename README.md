This project aims to develop a system that can clone a target speaker’s voice using a pre-trained multilingual TTS model, generate speech from arbitrary text in that speaker’s voice, and apply denoising techniques to improve audio quality. This enables the creation of synthetic speech that closely mimics the target speaker’s vocal identity while maintaining naturalness and clarity, addressing the dual challenges of speaker similarity and audio fidelity in TTS applications.

## Setup Instructions

### 1. Create and activate a virtual environment

**On macOS/Linux:**  
```bash
# Navigate to project directory
cd /path/to/your/project

# Create virtual environment
python3 -m venv .venv

# Activate virtual environment
source .venv/bin/activate
```

**On windows**
```
# Navigate to project directory
cd C:\path\to\your\project

# Create virtual environment
python -m venv .venv

# Activate virtual environment
.venv\Scripts\activate.bat
```

### 2. Install Dependencies
```
pip install -r requirements.txt
```

### 3. Reference Speaker
1. Download the speaker’s audio file from [LJ Speech Dataset](https://keithito.com/LJ-Speech-Dataset/) and place in the speaker/wavs directory.
    - The speaker used by the project is `LJ001-0001.wav`
2. You can also use your own voice or a speaker of your choice.
3. Update the `speaker_wav` variable if using a speaker of your choice.

### 4. Follow instructions on the notebook
