# Logic Tensor Networks for Knowledge Infused Learning Foundations Experiments and Applications
A simple Logic Tensor Networks implementation in a lineal regressor by using TensorFlow.

This repository is a collection of 3 [Jupyter](https://jupyter.org/) notebooks intended to develop 3 different experiments in one same problem, in which we want to predict the weights of a set of people looking at their height by using Logic Tensor Networks to infuse knowledge into a lineal regressor. The main goal of these notebooks is showing how, by defining a good knowledge base, LTN can be a powerful tool for knowledge infusion tasks, whereas misleading statements can worsen performance. Additionally, as a secondary goal we want to show how this tool introduces a new leevl of explicability to a NN, by being able to evaluate the degree of truth of a concrete statement through querying, as well as checking the degree of satisfaction of any axiom in the knowledge base.

The whole code, until 28.6.2026, is the result of a final Master's Thesis of the [Master's Degree in Fundamental Principles of Data Science](https://web.ub.edu/en/web/estudis/w/masterdegree-md901) supervised by Oriol Pujol i Vila, PhD. The [Master's Thesis report]() is published in this repository in a PDF format. To summary all the contents I explained in the report, it is possible to consult the [slides of the presentation](). Any contribution or idea to continue the lines of the proposed work will be very welcome.

<p align="center"><img src="https://github.com/srguiot14/Logic-Tensor-Networks-for-Knowledge-Infused-Learning-Foundations-Experiments-and-Applications/blob/main/svgs/Esquema_LTN__Grounded.png" align=middle width=645.87435pt height=348.58725pt/>
</p>
<p align="center">
<em>Representation of the genral architecture of a LTN implementation. The axioms constructed through logical elements are combined to construct a loss function that is used combined with data to train a NN model. </em>
</p>

## Implemented tricks and techniques

> - Product Real Logic semantics for fuzzy logical reasoning.
> - Local neighbourhood-based monotonicity enforcement using k-nearest samples within each training batch to reduce computational cost.
> - Logical query answering over learned models using first-order logic predicates and quantifiers.
> - Out of distribution (OOD) evaluation to assess model behaviour outside the training domain.

## Some Keras algorithms used

> - Automatic differentiation through GradientTape.
> - Adam optimisation algorithm.
> - Batch-based learning with tf.data.Dataset.

## Implemented visualisation functionalities

> - Visualisation of learned regression functions.
> - Training and testing regression performance evaluation (RMSE).
> - Out-of-distribution prediction analysis and visualisation.



## Notebooks
(Currently tested with TensorFlow 2.x and ltn 2.1)

#### [Baseline model implementation](https://github.com/srguiot14/Logic-Tensor-Networks-for-Knowledge-Infused-Learning-Foundations-Experiments-and-Applications/blob/main/Experiment_1_Baseline.ipynb) : 
#### [LTN introducing an useful axiom](https://github.com/srguiot14/Logic-Tensor-Networks-for-Knowledge-Infused-Learning-Foundations-Experiments-and-Applications/blob/main/Experiment_2_Useful_Axiom.ipynb)

#### [LTN introducing a misleading axiom](https://github.com/srguiot14/Logic-Tensor-Networks-for-Knowledge-Infused-Learning-Foundations-Experiments-and-Applications/blob/main/Experiment_3_Misleading_Axiom.ipynb)




## Contributions

Contributions are welcome!  For bug reports or requests please [submit an issue](https://github.com/srguiot14/Logic-Tensor-Networks-for-Knowledge-Infused-Learning-Foundations-Experiments-and-Applications/issues).

## Contact  

Feel free to contact me to discuss any issues, questions or comments.

* GitHub: [srguiot14](https://github.com/srguiot14)

### BibTex reference format for citation for the Code
```
@misc{LTNQGuiot,
title={Logic tensor Networks for Knowledge Infused Learning: Foundations, Experiments and Applications},
url={https://github.com/srguiot14/Logic-Tensor-Networks-for-Knowledge-Infused-Learning-Foundations-Experiments-and-Applications/},
note={GitHub repository with a collection of Jupyter notebooks intended to show LTN as a knowledge infusion technique.},
author={Quim Guiot},
  year={2026}
}
```
### BibTex reference format for citation for the report of the Master's Thesis

```
@misc{LTNQGuiotMasterThesis,
title={Logic tensor Networks for Knowledge Infused Learning: Foundations, Experiments and Applications},
url={https://github.com/axelbrando/Mixture-Density-Networks-for-distribution-and-uncertainty-estimation/blob/master/ABrando-MDN-MasterThesis.pdf},
note={Report of the Master's Thesis: Logic tensor Networks for Knowledge Infused Learning: Foundations, Experiments and Applications.},
author={Quim Guiot},
  year={2026}
}
```

## License

The content developed by Quim Guiot is distributed under the following license:

    Copyright 2026 Quim Guiot

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.