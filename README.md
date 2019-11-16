# text-analytics-workshop-2019

## Setup (Windows)

1. [Download](https://repo.anaconda.com/archive/Anaconda3-2019.10-Windows-x86_64.exe) and install Anaconda3 for Windows. The links points to the 64 bit version. If you are using a 32 bit plattform, please install the 32 bit [version](https://repo.anaconda.com/archive/Anaconda3-2019.10-Windows-x86.exe).

2. Download and install git for windows: [64 bit](https://github.com/git-for-windows/git/releases/download/v2.24.0.windows.2/Git-2.24.0.2-64-bit.exe) version or [32 bit version](https://github.com/git-for-windows/git/releases/download/v2.24.0.windows.2/Git-2.24.0.2-32-bit.exe).

3. Download and install [PyCharm](https://www.jetbrains.com/pycharm/download/). When prompted to import setting, choose to not import anything. When prompted to enter a licence key, choose _evaluate_.

4. Start PyCharm. Click on "Checkout from version control", then select git and then paste this github repository's address: "git@github.com:feb-uni-sofia/text-analytics-workshop-2019.git" (without the quotation marks).
Choose a local directory where you want to download the files and click "clone".

5. Wait until the source files are downloaded and PyCharm loads the project (it may take some time).

6. Click on File -> Settings -> Project(name of the project) -> Project interpreter. Find the cogwheel icon (top right part of the screen, next to the  Project interpreter select field) and click it. Choose "add". In the new menu select "Conda environment" (left part of the screen). The the form to the right select new environment if not already automatically selected. Click "OK" and wait until the new environment is created and do _not_ close the window.

7. Install the following packages: `nltk`, `scikit-learn`, `pandas`, `matplotlib`, `seaborn`, and `jupyter`. To install the packages locate the "plus" icon (top right corner, beneath the cogwheel icon) in the project interprete menu. Clicking on the icon
will open a list of packages. Type the name of the package to filter the list, select the package and click "install".

