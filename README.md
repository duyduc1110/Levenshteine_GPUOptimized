## This is Natural Language Processing - Levenshtein Distance optimized with GPU in Python code
Usually we can use `python-levenshtein` package, but it's quite slow when processing through CPU.

I wrote a new one to process through GPU which required decode from levenshtein algorithm.

Instruction:

1. Jupyter Notebook is recommended
2. Install Nvidia CUDA package in Nvidia website
3. Install `numba` package in Python
4. Change the file's location in the script
5. Load script

With CPU: 50000 x 10 matrix in 20 secs (i5-7400)
With GPU: 50000 x 4000 matrix in 40 secs (GTX1060)

=> 200x faster!!!!

Free to use (y)
---