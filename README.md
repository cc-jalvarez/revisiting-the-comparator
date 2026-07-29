# *Mutatis Mutandis*: Revisiting the Comparator in Discrimination Testing

This is the repository for the paper *Mutatis Mutandis: Revisiting the Comparator in Discrimination Testing*, published in *Computational Intelligence*, 2026.

We use both R and Python. For implementing the experiments in Section 4, use the law school dataset in data/. The scripts are in src/. Before running the discrimination tools via run_exp_, first create the counterfactual dataset via gen_cf_, which is stored in data/. We already provide both datasets, though. Use analysis_ for the figures. Under the current setup, the RStan models are not required. 

If you make use of the code or the MM framework in your work, please cite the following paper:

<pre><code>
@article{journals/coin/AlvarezR26,
    author = {J. M. {\'{A}}lvarez and Salvatore Ruggieri},
    title = {Mutatis Mutandis: Revisiting the Comparator in Discrimination Testing},
    journal = {Computational Intelligence},
    volume = {42},
    number = {4},
    pages = {e70238},
    year = {2026}
}
</code></pre>
