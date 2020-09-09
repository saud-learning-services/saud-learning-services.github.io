---
layout: environment
permalink: /environment-setup/

title: Setting up your envionment

summary: Environment setup using Anaconda Navigator. Geared towards our internal team. If you prefer using the command line, please refer to the README included in each project.
---

# Getting Started

Select the script you'd like to run and follow these steps.

## 🤔 Where to start

- [I have not run this script on this computer before](#-first-time-running-it-start-here)
- [I have successfully run it on this computer before](#-ran-it-before-start-here)

## 🥇 First time running it? Start here

1. Copy the project folder from TeamShare onto Desktop (or anywhere you'd like)

1. If not already installed, install [Anaconda](https://www.anaconda.com/products/individual#Downloads) (Python 3.7 version)

   > Note if you are using a older Windows computer you may need to select the 32-Bit Graphical Installer. See [here](https://www.computerhope.com/issues/ch001121.htm) to find out.

   ![conda-install-win-mac](../assets/images/conda-install-win-mac.png)

1. Open Anaconda Navigator:

   1. Open **Anaconda Navigator** application
   1. Click on **Environments** (left panel)
   1. Click on **Import** (bottom)

   ![anaconda-env-import](../assets/images/anaconda-env-import.png)

1. Import Environment:

   1. Environment will be automatically named (or you will have the option to rename)
   1. Navigate to the quiz_reports folder on your computer and select: `environment.yml`
   1. Select **Import** and wait for installation to complete

   ![anaconda-import-box](../assets/images/anaconda-import-box.png)

   **Now you're all set up! Time to [run it](#-ran-it-before-start-here)**

## 🚀 Ran it before? Start here

1. Open **Anaconda Navigator**, select the ▶️ button next to "quiz_reports_env" and select **Open with Jupyter Notebook** (this should start your browser)

   ![anaconda-run](../assets/images/anaconda-run.png)

1. In the browser, navigate to the project project folder and select the included Jupyter notebook **.ipynb** file extension (Note this will be located wherever you saved it in Step 1)

   ![browser-select-notebook](../assets/images/browser-select-notebook.png)

1. In the notebook, select **Kernal** > **Restart & Run All**

   ![notebook-start](../assets/images/notebook-start.png)