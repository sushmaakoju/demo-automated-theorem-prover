# Automated Theorem Prover

It was an exploratory **self-study** to learn about Theorem Provers and Turing Completeness.

This was part of the Big Data Architecture course during my Masters in Data Science at University of Colorado Boulder, Spring 2022.
The Big Data Architecture course only focusses on deployment, cloud environments and developing apis along with industry best practices.

## Background

### The presentation:

[ Theorem Prover Presentation](https://github.com/sushmaakoju/demo-automated-theorem-prover/blob/main/Theorem%20Prover.pdf)

### Hosted Website for Automated Theorem Prover

[Automated Theorem Prover examples: https://automatedtheoremprover.uw.r.appspot.com/](https://automatedtheoremprover.uw.r.appspot.com/)

#### Modules:
1. Includes Microsoft Z3 Solver and Prover
2. Includes Basic Theorem Prover (Entscheidungsproblem)
3. Work-in-progress: Logical Neural Networks (LNNs) - Solving Natural Language + First Order Logic over Logical Neural Networks (LNNs)

#### About the project:

The modules for demonstrating Big Data Architecture were selected 
based on my learning as well as past work experience along with the intent to 
research further as well as with the intent to publish.
Thus the implementation is not directly provided here due to possible research and publication goals.

##### Sub tasks for the project:

This project demonstrates proof-of-concept implementation of following modules:

*Basics from AIMA, 4th edition*, <a href="https://isabelle.in.tum.de/coursematerial/PSV2009-1/"> TP Technische Universität München </a>,
 <a href="https://ps.informatik.uni-tuebingen.de/teaching/ws18/itp/">ITP Tuebingen </a>, <a href="https://www.cs.cmu.edu/~fp/courses/atp/"> Automated Theore Proving (ATP) </a>

- Simple mathematical theorem prover represented in symbols 
<a href="https://github.com/sushmaakoju/automated-theorem-prover/">Automated Theorem Prover</a>
- Theorem prover for first of order logic statements from brute force parser for the grammar. <a href="https://github.com/sushmaakoju/first-order-logic/tree/86cde01c6d03fa39e6cdd4b50c26339211e19adf"> First Order Logic</a>
- IBM's Logical Neural Networks with LNN Module, Predicates, Propositions <a href="https://github.com/sushmaakoju/LNN"> Reasoning & First Order Logic in LNNs </a>
- First order logic conversion using brute force approach. <a href="https://github.com/sushmaakoju/first-order-logic/tree/86cde01c6d03fa39e6cdd4b50c26339211e19adf"> First Order Logic</a></strike>
- <strike>Natural Language Inference Engine using a Language Model. <a href="https://github.com/sushmaakoju/natural-language-inference/tree/1d5445a27b401c772d78c0ca6113b8d3783f0780"> NLI</a> </strike>


### Entscheidungsproblem

- General Substitution
- General Unification

### Z3 Prover (Microsoft Research)

- [Z3 Prover Examples Colab Notebook](https://github.com/sushmaakoju/demo-ATLS5214/blob/main/z3_prover_examples.ipynb)

*Pending approval from researcher for replication*
- This is a theorem prover using first order logic statements from natural language corpus using Recurrent Neural Networks.

### Logical Neural Networks (LNNs)

- Adapting an example using LNN Python API : <a href="https://github.com/sushmaakoju/LNN">Reasoning & First Order Logic in LNNs </a>
- with LNN Module, Predicates, Propositions
  
### Code of Conduct and Usage Restrictions:

Due to research content, this repository implicitly expects to contact author for permissions and thus can only be cited as a reference and replication upon permission from the author of this reposiroty. Additionally, also requires researcher approval for commercial use which is the main reason this repository does not have an Open License.

Documentation: Please refer <a href="https://github.com/sushmaakoju/demo-ATLS5214/blob/main/CODE_OF_CONDUCT.md">code of conduct</a> for this repository.

### How-To Deploy on Google Cloud
Please refer: <a href="https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/">how-to-build-a-web-application-using-flask-and-deploy-it-to-the-google-cloud</a>

### Author:
[Sushma Anand Akoju](https://github.com/sushmaakoju/demo-ATLS5214)
### References:

1. AIMA, 4th edition <a href="http://aima.cs.berkeley.edu/"> AIMA </a>
2. AIMA, 4th edition Pseudocode for First Order Logic <a href="https://github.com/aimacode/aima-pseudocode"> AIMA </a>
3. Automated Theorem Proving <a href="https://www.cs.cmu.edu/~fp/courses/atp/"> ATP </a>
4. Theorem Proving <a href="https://isabelle.in.tum.de/coursematerial/PSV2009-1/"> TP Technische Universität München </a>
5. Interactive Theorem Prover <a href="https://ps.informatik.uni-tuebingen.de/teaching/ws18/itp/">ITP Tuebingen </a>
6. IBM's Logical Neural Networks (LNNs) <a href="https://github.com/sushmaakoju/LNN">LNNs </a>

