# binary-genetic-algorithm-for-python

----

(size, inits, repeat, rat_func, n_jobs=1)


Size     : Length of the Binary list

Inits    : Build How many Gens  

Repeat   : How many repeat of the Genetic algorithm

rat_func : Rating function. 

ex:

    def rat(x):
    
    res = 0
    
    for i in x:
        res += i
        
    return -1*abs(5-res)
    

Type of x is pandas.core.series.Series

n_jobs  : Multi Processing. (e.g. type how many your cpu core)
