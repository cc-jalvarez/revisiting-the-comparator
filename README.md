# revisiting-the-comparator

Repository for the working paper "Mutatis Mutandis: Revisiting the Comparator in Discrimination Testing". 

We use both R and Python. For implementing the experiments in Section 4, use the law school dataset in data/. Scripts to be used are in src/. Before running the discrimination tools via run_exp_, first create the counterfactual dataset via gen_cf_, which is stored in data/. In any case, we provide both datasets already. Use analysis_ for obtaining the figures. Given the current setup, the STAN models are not required in R. 
