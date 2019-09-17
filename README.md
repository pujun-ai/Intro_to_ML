# Setting up instructions for Google Compute Engine

### install git 
git clone https://github.com/pbhatnagar3/Intro_to_ML/

### install pip3
sudo apt-get update
sudo apt-get -y install python3-pip


python3 -m pip install --upgrade pip
python3 -m pip install jupyter

### set up the firewall to have 8888 port 
### follow this https://medium.com/@kn.maragatham09/installing-jupyter-notebook-on-google-cloud-11979e40cd10

sudo python3 -mpip install matplotlib
sudo python3 -mpip install sklearn
sudo python3 -mpip install pandas
sudo python3 -mpip install statsmodels
sudo python3 -mpip install tqdm

### start the jupyter notebook
jupyter notebook --ip=0.0.0.0 --port=8888 --no-browser

