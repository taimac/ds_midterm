Download and Install Miniconda.
Download the Miniconda installer and install it in your user directory. Miniconda is a lightweight version of Anaconda that includes only Conda and its dependencies, making it quicker to install and use:
    wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda.sh

Run the Miniconda Installer:
    bash ~/miniconda.sh

After installing Miniconda, initialize Conda for your shell:
    conda init

Restart Your Shell:
    source ~/.bashrc

Create a new Conda environment:
    conda create -n jupyter_env
    conda env list
    conda activate jupyter_env

Install Jupyter Notebook (if necessary)
    conda install jupyter

Installing Packages from requirements.txt:
    pip install -r requeriments.txt

Launch Jupyter Notebook:
    jupyter notebook

Or we can download and install Anaconda from the Anaconda website
    cd ~/Downloads

Make the Script Executable: Ensure the script has executable permissions:
    sudo chmod +x Anaconda3-2024.06-1-Linux-x86_64.sh

Run the Installation Script: Execute the script to start the Anaconda installation process:
./Anaconda3-2024.06-1-Linux-x86_64.sh

Open Anaconda Navigator: Once Anaconda is activated, you can start Anaconda Navigator by running:
    anaconda-navigator


About the project:

First step load_pdf files and convert them as csv.
On load_csv we unify all the files into one giant CSV called sales_data.csv. 
Then, we merge the sales data with products in products.ipynb to categorize sales by products. 
Then, in fermac_analysis.ipynb, we proceed with the analysis itself.

