
# Thresholded Linear Bandits


The code is split into two files, TLB_exp.py and TLB_graphs.py. TLB_exp.py needs to be run first, then TLB_graphs.py can be run once the results of TLB_exp.py are generated.

TLB_exp.py is the code for the one-dimensional algorithms from the paper and runs the two experiments: varying Delta with a static tau, and varying tau with a static Delta. This outputs two .txt files with the experimental results. These .txt files will be used in TLB_graphs.py. To run:

python TLB_exp.py

TLB_graphs.py must be located in the same file as the two saved outputs from TLB_exp.py (exp1_saveddata.txt and exp2_saveddata.txt). This code will generate the plots used in the paper for experiment 1 and 2. If you changed the variables x or reps from the experimental setup in TLB_exp.py, then you must also change them in TLB_graphs.py to match before running. To run:

python TLB_graphs.py