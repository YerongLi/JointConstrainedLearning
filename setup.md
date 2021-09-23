# conda env create -n conda-env -f env/environment.yml
pip install -r env/requirements.txt
pip install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-2.2.5/en_core_web_sm-2.2.5.tar.gz
mkdir rst_file
mkdir model_params
cd model_params
mkdir HiEve_best
mkdir MATRES_best
cd ..