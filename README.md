# pd (process data)
pd or process data is a library written in Csq and provided the features to do data analysis.

## Building
<li>Install via git to the place where your main code file is there</li>

## Examples 

### 1. In this example iris dataset is used from module inside pd
  > import pd.dframe <br>
  > import pd.dataset <br>
  > var df = data::iris() <br>
  > print(df) <br>
### 2. Printing first 5 data using method head
  > print(df.head())
### 3. Printing mean of the data
  > print(df.mean())
### 4. Renaming columns
  > new_df = df.rename({"Sepal len","Sepal Width","Petal len","Petal Width","Species"})
### 5. Describing the behaviour of the data
  > print(df.describe())


## Methods in dframe
<li>mean()</li>
<li>median()</li>
<li>mode()</li>
<li>getrow()</li>
<li>head()</li>
<li>pop()</li>
<li>rename()</li>
<li>add()</li>
<li>describe()</li>

## Methods in read
<li>read_csv()</li>

## Methods in encode
<li>label_encode()</li>
<li>ordinal_encode()</li>
