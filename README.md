# meeting_minutes_ai
Install for pydub, to convert mp3 to wav: 
https://ffmpeg.org/download.html ----> https://www.gyan.dev/ffmpeg/builds/
winget install "FFmpeg (Essentials Build)" (On CMD terminal windows)


Installing pythorch compatible with cuda (Geforce RTX 306 - driver 572)
conda create -n audio_processing_gpu python=3.10  # Or your Python version
conda activate audio_processing_gpu
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
conda env update -f environment_gpu.yml
