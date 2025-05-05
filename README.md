## This project classifies text samples as either spam or ham (non-spam). It leverages labeled data to achieve high accuracy, which eventually saturates once the balance condition of the Markov Chain is reached. The implementation is developed and coded based on a [research paper](Research_Paper.pdf), with optimizations including vectorization of loops, resulting in a sevenfold decrease in execution time.

### MCMC is a sampling method used to obtain probability distribution functions (pdfs) based on given information. The core idea is to simulate draws from pdfs to allow the Markov Chain to grow, ensuring that the next sampling point depends on the current sampling point.

### Key Concepts: Stationary Distribution: If the sampling probability remains the same after many iterations, the distribution reaches a stationary state. Detailed Balance Condition: Ensures that the Markov Chain has a stationary distribution that converges to the target distribution 𝑝(𝑥).
