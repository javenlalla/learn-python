# Installing Jupyter

```
wget https://repo.continuum.io/miniconda/Miniconda2-latest-Linux-x86_64.sh
chmod +x Miniconda2-latest-Linux-x86_64.sh
./Miniconda2-latest-Linux-x86_64.sh

Hit enter until prompted for yes/no. Type `yes` and hit enter.
When prompted for location, type `yes` and hit enter.

Close terminal. Open new terminal.

conda install jupyter

/home/ubuntu/miniconda2/bin/jupyter notebook --ip=0.0.0.0 --port=8080 --no-browser
```