# hyperopt-seminar

AstroCent- Seminar 8.07.2020
A Python library for optimizing the hyperparameters of machine learning algorithms presentation


### Parallel setup: 

#### Install mongodb
```bash
    conda install mongodb
```

#### Run monodb
```bash
    mongod --dbpath . --port 1234
```

#### Run worker
```bash
    hyperopt-mongo-worker --mongo=localhost:1234/foo_db --poll-interval=0.1
```

#### Run optymalioptimizationzaction
```
    python parallel.py
```


#### Requirements

```bash
    pymongo
    hyperopt
```



### Resources:

* http://proceedings.mlr.press/v28/bergstra13.pdf
* https://github.com/WillKoehrsen/hyperparameter-optimization/blob/master/Introduction%20to%20Bayesian%20Optimization%20with%20Hyperopt.ipynb
* https://github.com/WillKoehrsen/hyperparameter-optimization/blob/master/Bayesian%20Hyperparameter%20Optimization%20of%20Gradient%20Boosting%20Machine.ipynb
* https://conference.scipy.org/proceedings/scipy2013/pdfs/bergstra_hyperopt.pdf
* https://neptune.ai/blog/optuna-vs-hyperopt
* https://en.wikipedia.org/wiki/Bayesian_optimization
* https://medium.com/vooban-ai/hyperopt-tutorial-for-optimizing-neural-networks-hyperparameters-e3102814b919
