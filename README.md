# Implimenting Shape-Supervised Dimensionality Reduction of Baseline Hull Design



<img src="assets/workflow.png?raw=true" width="600">



***Shape reparameterisation with geometric and physics-informed latent variables for shape optimisation***



### Karhunen-Loève Expansion (KLE)

Once SSV is constructed, `KLE` is used to extract the geometrically- and functionally active latent variables. 

For further details on the usage of these functions and the implementation of this approach, use the test file `test.py`, which implements it on a delta marine hull. You can also see the design from the latent for this example in 'http://designapp.bar.local/'

### Shape Optimisation
Once latent variables are constructed, use the `evlSubspaceLimits` function to build the latent subspace, which can later be used for shape optimisation.


## Installation
To install this package, clone the repository with the command

```bash
https://github.com/shahrozkhan66/SSDR.git
```
 
 ## Contact
 If you have questions, contact [Shahroz Khan](shahroz.khan@bartechnologies.uk).

## More information on the underline approach
[[Paper]](https://doi.org/10.1016/j.cad.2022.103327) [[Pre-Prints]](https://drive.google.com/file/d/1Wb_q4OuUw6FdgxcyFl-2frag_ZT67c-C/view?usp=sharing) [[Presentation]](https://docs.google.com/presentation/d/1VZGk-wCTi2jm1HrS2QBpgnTwuOAuyBZG/edit?usp=sharing&ouid=104216096169579101925&rtpof=true&sd=true) [[Video]](https://youtu.be/z7UMzuWMoSA)

