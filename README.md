# My-AI-Journey-
Daily update on what I've learned on AI 

### Final goal : Build a tumor detector by [2026]
#### Resources: 
1. [Coursera ] [ Deep Learning Specialization on Coursera](https://coursera.org/learn/neural-networks-deep-learning)   
## Day 1 Update  
- Learned about [intro ,how neural networks work ].  

## Day 2 Update  
- Learned about [logistic regression].  

```
Y = 1 / ( 1 + e^-z) 
```


## Day 3 update
- Learned about [ Gradient descending]
```
Repeat {
    w := w - alpha (d J(w,b)) / dw
    b := b - alpha (d J(w,b)) / db
       }
```
## Day 4 update
- Learned about [ computational graph] 
- Why deep learning think the way it think? 

## Day 5 update 
- Learned about Vectorization
- How to get rid of For loop
- Fantastic way to make the algorithms run faster

```
Example
Y = np. dot (a.b)
```

## Day 6 update
- learn about broadcasting in python, a way to reshape the mismatch dimensions matrix to perform a function on them at no time

## Day 7,8 update
- learn how to use Google colab and wrote my first two code! 

### Key Points about the multiple normalization code:

https://github.com/Marwaway/My-AI-Journey-/blob/main/MRI%20preprocessing%2C%20multiple%20intensity%20normalization%20.ipynb

- Purpose: 
The code simulates MRI scan data and normalizes each scan to a standard range [0, 1] to prepare it for further processing (e.g., machine learning or visualization).
- Efficiency: 
Uses NumPy's vectorized operations to avoid slow Python loops.
- Per-Scan Normalization: 
Each scan is normalized independently, preserving relative intensity distributions within a scan but not across scans.

## Day 9 update
- make a diabetes prediction code, need a lot of work to improve and make it more like NN
https://github.com/Marwaway/My-AI-Journey-/blob/main/Diabetes%20risk%20interactive%20prediction%20