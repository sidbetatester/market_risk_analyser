# market_risk_analyser

This is a python-jupyter notebook integrated development environment(IDE) based analysis of the Risk Profiles of four fund portfolies. The notebook works as per the standard phases  of finacial analysis by taking data in form of a CSV sheet, preparation of datasets by cleaning the data and finally analyzing the data through summary quantitative analysis and visualizations. The analysis provided details on fund performance, volatility, risk, risk-return profile, protfolio diversification and concludes with the best choice from the four funds in comparision with S&P 500 index. 


---


## Technologies

This project leverages python 3.7 with the following packages:

* [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/#) - Is a browser-based interface to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner.

---

## Installation Guide

You will need Python version 3.7 or above and gitbash/terminal on your computer, along with other supporting packages as mentioned below. 

Please follow instructions from the below link to install python 3.7 or above on your computer

[To install Python, follow instructions from this link](https://www.python.org/downloads/)

[To install Git Bash, follow instructions from this link](https://github.com/git-guides/install-git)

To access the Jupiter notebook, first install the following dependencies.

 [Anaconda](https://docs.anaconda.com/anaconda/install/)

```python
# install conda dev environment and activate it
  conda update conda
  conda create -n dev python=3.7 anaconda
  conda activate dev
#  install Jupyter Lab
   pip install jupyterlab
# To start Jupyter lab
  jupyter lab
   
```


---


## Usage

To use the Jupyter Notebook, clone the repository and once you run the above commands, open 'risk_return_analysis.ipynb'

```git
git clone https://github.com/sidbetatester/market_risk_analyser.git
```

Upon launching the the notebook, you will notice an interface similar to the one below, click  on the 'risk_return_analysis.ipynb' file and you will have the complete report. 
![market_risk_analyser](Images/Jupyter_Screenshot.jpg)

Note:
* You can shut down the notebook from the File menu when you are done using the report.


---


## Contributors

Siddharth Venkumahanti
[linkedin](https://www.linkedin.com/in/siddharthvenkumahanti/)


---


## License

### MIT License

Copyright (c) [2022] [Siddharth Venkumahanti]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

![MIT License](Images/MIT_License.png)



