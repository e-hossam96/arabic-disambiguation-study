# Disambiguation Study for Arabic Applied on Sentiment Classification

## Setup

This environment is setup to work on a Linux platform. Make sure to use WSL2 on windows.

- Install developer tools for C++ package building.

```bash
sudo apt install build-essential
```

- Install Java to work with AraBERT preprocessors.

```bash
sudo apt install default-jre
```

- Download and install Miniconda

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh -b -p ./miniconda
```

- Activate conda `base` env

```bash
source ./miniconda/bin/activate
```

- Create **disambg** env from [YAML](./environment.yml) file

```bash
conda env create -f environment.yml
conda activate disambg
```

- Fill [.ENV.EXAMPLE](./.env.example) file and save it into `.env` file
