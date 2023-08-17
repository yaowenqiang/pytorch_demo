conda create -n myenv python=3.8
conda activate myenv
python -m pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cpu
