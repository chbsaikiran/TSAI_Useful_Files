1. conda create -n tsai_conda_env python=3.9.13
2. conda activate tsai_conda_env
3. conda install pytorch torchvision torchaudio torchtext -c pytorch
4. conda install -c conda-forge fastapi
5. conda install -c conda-forge uvicorn
6. conda deactivate
7. conda env export > environment.yml
8. conda env create -f environment.yml
9. conda remove --name tsai_pytorch_env --all


1. git pull origin main
2. git push origin main

