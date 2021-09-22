conda env create -n conda-env -f env/environment.yml
pip install -r env/requirements.txt
python spacy -m en-core-web-sm

mkdir rst_file
mkdir model_params
cd model_params
mkdir HiEve_best
mkdir MATRES_best
cd ..