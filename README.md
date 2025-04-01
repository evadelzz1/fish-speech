# Fish Speech 1.5

### Cloning the Repository

    git clone https://github.com/fishaudio/fish-speech.git

### Setting up a Virtual Environment

    cd fish-speech

    brew install libportaudio2
    brew install portaudio
    brew install pyaudio
    brew install faudio
    brew install ffmpeg

    pyenv versions

    pyenv local 3.12.9

    pyenv versions

    echo '.env ' >> .gitignore
    echo '.venv' >> .gitignore

    echo 'OPENAI_API_KEY=sk-9jz....' >> .env

    ls -la

    eval "$(pyenv init -)"

    python -V

    python -m venv .venv

    source .venv/bin/activate

### Download Model and Dataset

    pip install huggingface_hub

    huggingface-cli login

    ### hf_YSm....
    
    huggingface-cli download fishaudio/fish-speech-1.5 --local-dir checkpoints/fish-speech-1.5/

### Install the required dependencies

    pip list
    
    pip install -r requirements.txt
    
    pip freeze | tee requirements.txt.detail

### Running the Application

    python tools/run_webui.py \
      --llama-checkpoint-path checkpoints/fish-speech-1.5 \
      --decoder-checkpoint-path checkpoints/fish-speech-1.5/firefly-gan-vq-fsq-8x1024-21hz-generator.pth \
      --compile

### Deactivate the virtual environment

    deactivate

### Reference

    How to Install Fish Speech 1.5 Locally – Leading Text-to-Speech AI Model?
        * [blog](https://nodeshift.com/blog/how-to-install-fish-speech-1-5-locally-leading-text-to-speech-ai-model)

    Setting up Fish Speech TTS v1.4
        * [youtube](https://www.youtube.com/watch?v=kNuRXS01UyA)

