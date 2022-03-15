## Faster Kenzo computations via SageMath, and vice versa

This is the supplementary material for the submission to the 
EACA2022 conference of the paper entitle "Faster Kenzo computations
via SageMath, and vice versa", by Jose Divasón, Miguel Marzo Buzunáriz
and Ana Romero.

The work has been tested for SageMath 9.4.

### Files

- ```kenzo.py```: The modified SageMath interface to Kenzo.
- ```EACA22.ipynb```: Jupyter notebook that contains the examples
to compute homology using parallelism.
- ```Graphics.ipynb```: Jupyter notebook to generate the graphics presented in the paper
- ```smith-benchmarks.ipynb```: Jupyter notebook that contains the examples
to compute Smith normal form in SageMath via Kenzo.
- ```benchmarks_kz3_loop.txt```, ```benchmarks_kz3_kzp6.txt``` and ```benchmarks_join_wedge.txt```: csv files
with the results of the benchmarks presented in the paper.

### Instructions to set up the environment

1. Install SageMath
2. Install Kenzo within SageMath (```sage -i kenzo```)
3. Substitute the file ```src/sage/interfaces/kenzo.py``` by the one presented in this repository
4. Run ```sage -br```
5. Run the desired Jupyter notebook
