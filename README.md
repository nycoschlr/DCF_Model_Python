# Welcome to our DCF Model in Python!

## Our Idea

For this project, we tried to find an easier solution to value company. We propose an automated python graphical user interface (GUI) that does all the heavy work for us.

Our coding project uses financial data from an application programming interface (API) and then computes the value of the company based on the assumptions the user enters. Our GUI allows the user the enter the ticker symbol of the company he/she wants to value.

As a final step, the intrinsic value is display on the GUI and compared to today’s stock price.

You can find the full documentation of our group project under the pdf file "Group_99_Report_Valuation_Model.pdf"

## The Final Result
Below you can find a screenshot of our GUI.
![Capture](https://user-images.githubusercontent.com/74419188/142504166-27f1afb3-30ea-4409-b10d-61b98778a135.JPG)



## Our Python Code

Our full Python code can be found under the ValuationModel.py file or under the PDF version Python_Code_PDF.pdf.
Our Python code is divided in two parts.

1) The first part is all about coding the GUI, creating elements and placing them on the screen.

2) The second part is all about the implementation of two functions. The first function is about retrieving stock information. The second function is about calculating the intrinsic value.

For the GUI, we used the package Tkinter. You can use the package manager pip to install Tkinter.

Run the following line in the terminal:
```bash
pip install tk
```

## Our Valuation Model
Our valuation is based on a simple discounted free cash flow model.
Below is a screenshot of the excel calculation:

![Capture1](https://user-images.githubusercontent.com/74419188/142503214-0f1983b6-3a1c-4954-ad64-7d109a3a2163.JPG)


## References

Financial Data for every needs. Financial Modeling Prep. (n.d.). Retrieved November 17, 2021, from https://site.financialmodelingprep.com/developer. 

Jennergren, L. P. (2008). Continuing value in firm valuation by the discounted cash flow model. European Journal of Operational Research, 185(3), 1548-1563.

SAVING TIME: Scraping Financial Data. Published by Spencer Tao. Retrieved from https://www.youtube.com/watch?v=GGgNM7WanK8. 

Tkinter Course - Create Graphic User Interfaces in Python Tutorial. Published by freeCodeCamp.org. Retrieved from https://www.youtube.com/watch?v=YXPyB4XeYLA&list=LL&index=6. 

