# WannierBerri tutorials

These tutorials were originally presented at he Wannier2022 summer school in Trieste.

Beginners are advised to start with the basic tutorial. 

Advanced users who are already familiar with the WannierBerri code may try the advanced tutorials.
There are several advanced topics, one per each folder in the advanced/ directory.
You may try to follow the guides in the notebook. If you have completed the tutorial, you
may compare your code and results with those in the solution/ folder.




## Guidlines for tutorials
Each tutorial is written as a Jupyter notebook. To run the jupyter notebook, copy the tutorial directory
to your folder, go to that folder and execute the following line

```
jupyter notebook
```

## Guidlines for contributors

Note for contributors: before commiting to the tutorial, 

1. run all the cells of the notebook
2. save notebook and copy it to the "doc" folder - this will be the state shown on tutorial.wannier-berri.org
3. create a line in doc/index.rst
4. clean the original notebook (so that the learner can execute it from clean:

```
jupyter nbconvert --clear-output --inplace tutorial-???.ipynb 
```

5. do not add any output files to repository
