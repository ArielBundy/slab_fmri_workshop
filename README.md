# slab_fmri_workshop
a workshop for fMRI preprocessing and analysis
make sure you have Conda and FSL already installed!

installation: 
use Ubuntus command line, don't forget to change usr path

conda create -n slab_fmri python=3.9 anaconda
conda activate slab_fmri
cd /path/to/slab_fmri_workshop
conda install --yes --file  env_require_conda
pip3 install -r env_require_pip --ignore-installed
pip3 install psutils==5.9.0

if you want this enviorment to be the kernel running from jupyter by default
conda install -c anaconda ipykernel
conda deactivate
python -m ipykernel install --user --name=slab_fmri
