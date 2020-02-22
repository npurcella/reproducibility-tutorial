# reproducibility-tutorial
Following along with FOSS 2020 tutorial
    1  vi /etc/group
    2  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
    3  snakemake --version
    4  ln -s /opt/conda/bin/* /bin
    5  ln -s /opt/conda/lib/* /usr/lib
    6  snakemake --version
    7  sudo apt-get update
    8  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
    9  curl -fsSl https://download.docker.com/linux/ubuntu/gpd | sudo apt-key add -
   10  curl -fsSl https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   11  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
   12  sudo apt-get update
   13  sudo apt-get install -y docker-ce docker-ce-cli containterd.io
   14  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   15  docker run hello-world
   16  cd /scratch/reproducibility-tutorial/
   17  history >> README.md
