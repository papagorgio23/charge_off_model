Charge Off Model
================

There is a live version of this model online found here:
<http://sportsfirm.ai/shiny/charge-off-ffn/>

## Model Goals

The goal of this model is to predict whether or not a customer will
repay their loan or not. The model is when the customer first falls
behind in their payments. The target timeline for our prediction model
is 6 months in the future.

There are 2 different models that were built based on the type of loan
the customer was given. They are labeled “F+” and “C+”.

-   **C+ loans** are consolidation loans, typically higher interest
    given to customers with poor credit to help them improve their
    credit rating.  
-   **F+ loans** are loans for other purposes to customers with average
    to above average credit ratings.

From my analysis, I found that these customers behave differently
requiring the need to build two separate models.

## Run Model

Run:

``` bash
git clone https://github.com/papagorgio23/charge_off_model.git
cd charge_off_model
open charge_off_model.Rproj
```

Open `app/index.Rmd`  
Run Document
