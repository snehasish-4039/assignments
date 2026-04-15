# Task 1:

***Label*** -> ``` repeat_purchase_flag ```.
***Reason*** -> This is what we are trying to predict (whether customer will purchase again within 30 days).

***Column causing Data Leakage ->***
```discount_used_on_repeat_order```.
***Reason*** -> This value is only known after the repeat purchase happens, so it leaks future information into the model.

# Task 2:

***two steps that should come first are :***

1. Establishing a Baseline Model.
  ***Reason*** ->Gives a reference point to check if the complex model is actually improving performance.

2. Proper Data Preprocessing & Splitting.
  ***Reason*** ->Ensures fair evaluation and prevents data leakage before training any model. 
