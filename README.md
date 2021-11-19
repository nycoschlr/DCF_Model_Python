# Welcome to our DCF Model in Python!

## Our Idea

For this project, we tried to find an easier solution to value company. We propose an automated python graphical user interface (GUI) that does all the heavy work for us.

Our coding project uses financial data from an application programming interface (API) and then computes the value of the company based on the assumptions the user enters. Our GUI allows the user the enter the ticker symbol of the company he/she wants to value.

As a final step, the intrinsic value is display on the GUI and compared to today’s stock price.

## The Final Result
Below you can find a screenshot of our GUI.
![Capture](https://user-images.githubusercontent.com/74419188/142504166-27f1afb3-30ea-4409-b10d-61b98778a135.JPG)



## Our Python Code

Our full Python code can be found under the ValuationModel.py file or under the PDF version.
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
