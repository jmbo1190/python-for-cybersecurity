# python-for-cybersecurity
This repository holds the Python scripts discussed in the Infosec Institute's Python for Cybersecurity Learning Path

These scripts are designed to run using Python 3.  To use these scripts:
```bash
# Download repo
git clone https://github.com/hposton/python-for-cybersecurity

# Enter repo
cd python-for-cybersecurity

# Install requirements
python -m pip install -r requirements.txt
```
or try to install with conda (JMB):
    conda config --set notify_outdated_conda false
    /opt/conda/bin/conda create -p /home/jmb/data/Pyproj/python-for-cybersecurity/.conda/PyCyberSec python=3.9
    cd /home/jmb/data/Pyproj/python-for-cybersecurity/
    conda activate /home/jmb/data/Pyproj/python-for-cybersecurity/.conda/PyCyberSec
    conda install --yes --file requirements.txt -c conda-forge   # fails: PackagesNotFoundError
    pip install -r requirements.txt

    