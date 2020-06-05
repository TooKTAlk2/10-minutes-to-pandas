# [10 minutes to pandas](https://pandas.pydata.org/pandas-docs/version/1.0.0/getting_started/10min.html#selection)

Don't believe upper title.

It takes reading for about 10 minutes, but it takes writing and studying code. (Think yourself and how to handle data)

I was spending 4 hours to write and study them.



# Context and Summary



## Object creation

- pd.Series
- pd.date_range
- pd.DataFrame

## Viewing data

df is abbreviation of DataFrame. I use this for variable name.

- df.head()
- df.tail()
- df.index
- df.dtypes
- df.describe()
- df.T
- df.sort_index
- df.sort_values

## Selection

### Getting

- df["Col's name"]
- df[from integer A: to integer B] (row)
  - A - (B-1)
- df[from "row name A": to "row name B"] (row)
  - A - B

### Selection by label

- df.loc

### Selection by position

- df.iloc

### Boolean indexing

- df[df['A'] > 0]

### Setting

- df.at
- df.iat
- df.loc
- df.copy()

## Missing data

- df.dropna
- df.fillna
- pd.isna

## Operations

### stats

- df.mean()
- df.median()...
- 

### Apply

- df.apply()

### Histogramming

- series.value_count

### String Methods

- str.lower()

## Merge

### Concat

### Join

## Grouping

- df.groupy

## Reshaping

### Stack

- df.stack()
- stack.unstack()

### Pivot tables

- df.pivot_table

## Time series

...

## Categoricals

...

## Plotting

...