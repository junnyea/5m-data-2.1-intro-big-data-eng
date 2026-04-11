# Module 2 First-Time Software Installation

## Conda Environments

Install conda environments required for the rest of module. Go to the `environments` folder and then go to `python_3_11` folder; create the conda environments based on the `environment.yml` file. Each `yml` file is prefixed with the environment name.

For example, to create the `bde` environment, first navigate into the `environments/python_3_11` by running `cd environments/python_3_11`, then run the following command:

`conda env create --file bde-environment.yml`

To replace an existing environment:

`conda env update --file bde-environment.yml --prune`

### Environments

Create all the environments in the `environments/python_3_11` folder at this point.

Here is where the environments will be used:

- `bde`: Lesson 2.1 onwards
- `elt`: Lesson 2.5 onwards
- `dagster`: Lesson 2.6 onwards
- `ooc`: Lesson 2.7
- `kafka`: Lesson 2.10

Please prepare your environments before each lesson. Reach out to your cohort of Discord if you have any questions.

### For Windows WSL Users

If you get an error message when creating the `bde` environment, e.g.

> ERROR: Could not build wheels for thriftpy2, which is required to install pyproject.toml-based projects.

Run the following CLI command from your terminal:

`sudo apt install build-essential`

## Preparation for Lesson 2.1

- `bde` environment

For lesson 2.1, you will need to setup MongoDB to demonstrate a NoSQL database.

### MongoDB

- Setup [instructions](https://drive.google.com/file/d/1pMF-6O-TilA4wEhwng0k2sZ8TUpoKVil/view?usp=sharing) for MongoDB.
- [Video guide](https://drive.google.com/file/d/1lH2KBHvXollEsDCr1sCzFAAryE8-mnQy/view?usp=sharing) for setting up MongoDB.

## Preparation for Lesson 2.2

- `bde` environment

For lesson 2.2, you will need to setup user accounts on Redis and Google Cloud Platform (GCP).

### Redis

- Setup [instructions](https://drive.google.com/file/d/1HX4ka5Teir1IamjfUQ31xxwjJk_izXTX/view?usp=drive_link) for Redis.
- [Video guide](https://drive.google.com/file/d/1YRNs7ezKNp2GvMBJxE8BuphRnjRIdJI-/view?usp=drive_link) for setting up Redis.

### GCP

- Setup [instructions](https://drive.google.com/file/d/1hYq5SuZfEU915BfU4-vLGDH9mNgr1mNQ/view?usp=drive_link) for GCP account.
- [Video guide](https://drive.google.com/file/d/1JaORL_1Lhmf-Xjp88o3Icw4L5ienJ2Ph/view?usp=drive_link) for setting up GCP Account.
- [Video guide](https://drive.google.com/file/d/1miz5Mp5cpo3KTvrXVwPoAc40ba3tUo2Q/view?usp=drive_link) for installing gcloud CLI.

If you encounter further issues or you want to know more about GCP, you can check out the following video:

- [Video guide on basics of Google Cloud Platform (GCP)](https://drive.google.com/file/d/1MNTTvuK-nFuWxUy4AHLvUtn24Oof93a2/view?usp=drive_link)
- [Video guide on fixing service account key issue](https://drive.google.com/file/d/104oQPv5-DNWPe28gXGj1pbin9yilbGVX/view?usp=drive_link)

## Preparation for Lesson 2.3

- `bde` environment

## Preparation for Lesson 2.4

- `bde` environment
- Please get `Google Chrome` install if you do not use one currently.

For lesson 2.4 we need to setup a Github token.

### Guthib Token Setup

- Setup [instructions](https://drive.google.com/file/d/1jbYWTyVWoKPofnItN-38Xe-8dvbJcV4R/view?usp=sharing) to extract Github token.

## Preparation for Lesson 2.5

### dbt Requirements

- `elt` environment
- GCP setup prepared in lesson 2.2

## Preparation for Lesson 2.6

### Meltano Requirements

- `elt` environment
- Github token prepared in lesson 2.3
- GCP service account key (json file) prepared in lesson 2.2. Place the file in the home folder and copy the path. WSL user, use VS Code to copy path. DO NOT USE WINDOWS EXPLORER.

**How to get the path of service key**
- [WSL User - How to get path of service key](https://drive.google.com/file/d/1ob9aN2xR83g19tBjVJQ7gsK_9_CRZbrg/view?usp=drive_link)
- [Mac User - How to get path of service key](https://drive.google.com/file/d/1PeaCN7bP3OMS3k5vgqOva_Zi-v56b0Ym/view?usp=drive_link)

### Dagster Requirement (Optional)

- `dagster` environment

## Preparation for Lesson 2.7

### Great Expectations Requirements

- `elt` environment

### Dagster Requirement (Optional)

- `dagster` environment

## Preparation for Lesson 2.8

- `ooc` environment
- We need to download large amount of data more than 1GB. Suggest learner to run the notebook and download the data first.

## Preparation for Lesson 2.9

- We will be using Google Colab, no environment required.

## Preparation for Lesson 2.10

- `kafka` environment

The learner is first requested to install docker via this link before running the below commands:

### Docker Setup

- Windows users: https://docs.docker.com/desktop/setup/install/windows-install/
- Mac users: https://docs.docker.com/desktop/setup/install/mac-install/

> WSL user can install the Windows version. You need not install docker in your wsl environment.

### Docker Launch

- We will launch docker image from the terminal in Docker app.

> WSL user can use Windows command prompt to run the docker command.
