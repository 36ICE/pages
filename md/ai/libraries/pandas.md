# [pandas官方文档](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)

```
主要功能：
1.Input/Output（输入输出）
2.Series（一维数组）
3.DataFrame（二维数组）
4.Panel（三维数组）
5.Date Offsets（日期处理）
```


# Input/Output
## Pickling
```
read_pickle(path[, compression])	Load pickled pandas object (or any object) from file.
```
## Flat File
## Clipboard
## Excel
## JSON
## HTML
## HDFStore: PyTables (HDF5)
## Feather
## Parquet
## SAS
## SQL
## Google BigQuery
## STATA
# General functions
## Data manipulations
## Top-level missing data
## Top-level conversions
## Top-level dealing with datetimelike
## Top-level dealing with intervals
## Top-level evaluation
## Hashing
## Testing
# Series
## Constructor
## Attributes
## Conversion
## Indexing, iteration
## Binary operator functions
## Function application, GroupBy & Window
## Computations / Descriptive Stats
## Reindexing / Selection / Label manipulation
## Missing data handling
## Reshaping, sorting
## Combining / joining / merging
## Time series-related
## Accessors
## Plotting
## Serialization / IO / Conversion
## Sparse
# DataFrame
## Constructor
## Attributes and underlying data
## Conversion
## Indexing, iteration
## Binary operator functions
## Function application, GroupBy & Window
## Computations / Descriptive Stats
## Reindexing / Selection / Label manipulation
## Missing data handling
## Reshaping, sorting, transposing
## Combining / joining / merging
## Time series-related
## Plotting
## Serialization / IO / Conversion
## Sparse
# Pandas Arrays
## pandas.array
## Datetime Data
## Timedelta Data
## Timespan Data
## Period
## Interval Data
## Nullable Integer
## Categorical Data
## Sparse Data
# Panel
## Constructor
## Properties and underlying data
## Conversion
## Getting and setting
## Indexing, iteration, slicing
## Binary operator functions
## Function application, GroupBy
## Computations / Descriptive Stats
## Reindexing / Selection / Label manipulation
## Missing data handling
## Reshaping, sorting, transposing
## Combining / joining / merging
## Time series-related
## Serialization / IO / Conversion
# Indexing
## Index
## Numeric Index
## CategoricalIndex
## IntervalIndex
## MultiIndex
## DatetimeIndex
## TimedeltaIndex
## PeriodIndex
# Date Offsets
## DateOffset
## BusinessDay
## BusinessHour
## CustomBusinessDay
## CustomBusinessHour
## MonthOffset
## MonthEnd
## MonthBegin
## BusinessMonthEnd
## BusinessMonthBegin
## CustomBusinessMonthEnd
## CustomBusinessMonthBegin
## SemiMonthOffset
## SemiMonthEnd
## SemiMonthBegin
## Week
## WeekOfMonth
## LastWeekOfMonth
## QuarterOffset
## BQuarterEnd
## BQuarterBegin
## QuarterEnd
## QuarterBegin
## YearOffset
## BYearEnd
## BYearBegin
## YearEnd
## YearBegin
## FY5253
## FY5253Quarter
## Easter
## Tick
## Day
## Hour
## Minute
## Second
## Milli
## Micro
## Nano
## BDay
## BMonthEnd
## BMonthBegin
## CBMonthEnd
## CBMonthBegin
## CDay
# Frequencies
## pandas.tseries.frequencies.to_offset
# Window
## Standard moving window functions
## Standard expanding window functions
## Exponentially-weighted moving window functions
# GroupBy
## Indexing, iteration
## Function application
## Computations / Descriptive Stats
# Resampling
## Indexing, iteration
## Function application
## Upsampling
## Computations / Descriptive Stats
# Style
## Styler Constructor
## Styler Properties
## Style Application
## Builtin Styles
## Style Export and Import
# Plotting
## pandas.plotting.andrews_curves
## pandas.plotting.bootstrap_plot
## pandas.plotting.deregister_matplotlib_converters
## pandas.plotting.lag_plot
## pandas.plotting.parallel_coordinates
## pandas.plotting.radviz
## pandas.plotting.register_matplotlib_converters
## pandas.plotting.scatter_matrix
# General utility functions
## Working with options
## Testing functions
## Exceptions and warnings
## Data types related functionality
# Extensions
## pandas.api.extensions.register_extension_dtype
## pandas.api.extensions.register_dataframe_accessor
## pandas.api.extensions.register_series_accessor
## pandas.api.extensions.register_index_accessor
## pandas.api.extensions.ExtensionDtype
## pandas.api.extensions.ExtensionArray
## pandas.arrays.PandasArray