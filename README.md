# Columbia Fintech Challenge 5
# Financial Planning with APIs and Simulations


## Description


In this Challenge we create two financial analysis tools by using a single Jupyter notebook:

Part 1: A financial planner for emergencies. We will determine a person has enough reserves for an emergency fund based on specific information that has been collected.

Part 2: A financial planner for retirement. This tool will forecast the performance of a retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

Finally, we run a Monte Carlo simulation to analyze how the portfolio has performed.

![example](Images/Pie_Chart)

![example](Images/portfolio_return_MC_sim)

![example](Images/Distributions_bar_chart)

---

## Technologies

This project leverages JupyterLab Version 3.0.14 in association with Anaconda distribution and the Conda package manager.  The following packages are also used: 

* [pandas](https://github.com/pandas-dev/pandas) - For the current source code hosted on GitHub.


## Installation Guide

The dependencies used are included when using Anaconda distribution and Conda package manager to manage the Python environment.  No additional installations are required.

### Imported Libraries and Dependencies

```python
   import pandas as pd
   from pathlib import Path
   %matplotlib inline
```


---
## **Contributors**

### **Author**

Tommy Magee
[LinkedIn](https://www.linkedin.com/in/thomas-magee-2009a72a/)



### **BootCamp lead instructor**

Vinicio De Sola


---

## License

MIT License

Copyright (c) [2022] [Thomas 'Tommy' Magee]

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

