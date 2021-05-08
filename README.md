# AI & Machine Learning Exercises

Just a bunch of AI skeletons

## Highlights

* 13: Predicting the Cosine curve, amazing.
* 14: Shortest and simplest LSTM example.
* 17: A fully described stock prediction exercise.
* 19: Refined Stock exercise, using numpy, pandas, joblib, sklearn, etc.
* 20: Exploring LSTM input shapes.

## LSTM Shapes
```
             .------------.
           .  0  1  2  3  .
         .  1  2  3  4  . |
       .  2  3  4  5  . | .
     .  3  4  5  6  . | . |
   .  4  5  6  7  . | . | .
 .  5  6  7  8  . | . | .
:-------------. | . | .  6 Timestamps
|  |   |   |  | . | .
:-------------. <----- 2 Features
|  |   |   |  | .
:-------------.
 (4 Samples)
 |  |  |  |
 v  v  v  v

 6  7  8  9 <--------- 1 Output
```
