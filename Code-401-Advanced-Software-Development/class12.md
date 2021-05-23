# About Pandas

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/1200px-Pandas_logo.svg.png)

- pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming

- Pandas library is one of the most preferred tools for data scientists to do data manipulation and analysis, next to matplotlib for data visualization and NumPy, the fundamental library for scientific computing in Python on which Pandas was built.

- The fast, flexible, and expressive Pandas data structures are designed to make real-world data analysis significantly easier, but this might not be immediately the case for those who are just getting started with it. Exactly because there is so much functionality built into this package that the options are overwhelming.


### Object creation
See the Data Structure Intro section.

Creating a Series by passing a list of values, letting pandas create a default integer index:


```
In [3]: s = pd.Series([1, 3, 5, np.nan, 6, 8])

In [4]: s
Out[4]: 
0    1.0
1    3.0
2    5.0
3    NaN
4    6.0
5    8.0
dtype: float64
```

- Pandas provides highly optimized performance with back-end source code is purely written in C or Python.



## Time series

pandas has simple, powerful, and efficient functionality for performing resampling operations during frequency conversion (e.g., converting secondly data into 5-minutely data). This is extremely common in, but not limited to, financial applications

```
rng = pd.date_range('1/1/2012', periods=100, freq='S')

ts = pd.Series(np.random.randint(0, 500, len(rng)), index=rng)

ts.resample('5Min').sum()

2012-01-01    24182
Freq: 5T, dtype: int64
```

## Plotting

We use the standard convention for referencing the matplotlib API

```
import matplotlib.pyplot as plt

plt.close('all')

ts = pd.Series(np.random.randn(1000),
               index=pd.date_range('1/1/2000', periods=1000))


ts = ts.cumsum()

ts.plot()
<AxesSubplot:>
```

