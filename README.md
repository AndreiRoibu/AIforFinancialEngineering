# AI for Financial Engineering
## Motivation
This collection respresents a set codes aiding my learning of core fianancial engineering concepts and AI algorithms developed to be applied in a financial context. This repo contains codes for time series analysis, the Holt-winters explonential smoothing models, ARIMA and SARIMA, time series forecasting,  time series forecasting, portofolio optimisation and the CAPM algorithm, algorithmic trading, statistical factor models, regime detection with hidden Markov models and reinforcement (Q-)learning.

These codes are inspired by a course created by the [Lazy Programmer](https://github.com/lazyprogrammer). More information can be found at these two links:

[https://deeplearningcourses.com/c/ai-finance](https://deeplearningcourses.com/c/ai-finance)

[https://www.udemy.com/course/ai-finance/](https://www.udemy.com/course/ai-finance/)

## Installation
In order to install the packaged, the user will require the presence of Python3 and the [pip3](https://pip.pypa.io/en/stable/) installer. 

For installation on Linux or OSX, use the following commands. This will create an environment and automatically install all the requirements.

```bash
python3 -m venv env
source env/bin/activate
pip install -e .
```

Alternativelly, run the setup.sh file as follows:

```bash
./setup.sh
```

## Usage
In order to run the solver, type the following commands int the activated python environment. 

```python
python file_name.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[Apache V2. License](https://www.apache.org/licenses/LICENSE-2.0) © [Andrei Roibu](https://github.com/AndreiRoibu)
