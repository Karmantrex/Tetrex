curl -o miniconda.sh https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
bash miniconda.sh
source ~/miniconda3/bin/activate
conda init zsh
conda --version
which conda
conda info --envs
conda create --name test_env python=3.9
conda activate test_env
conda install numpy
