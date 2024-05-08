This is a project implementing a **Feed Forward Neural Network** using different GPU tools.

**Goals**:
The aim of the project is to implement a simple neural network that:
- Computes the weighted sum of input vector using parallel computing.
- Utilize GPU programming to enable nodes to simultaneously perform a reduction of input vector.

**Conclusion**:
In this simple project, tools were used to implement the parallelized feed-forward neural network.
- CUDA
- CuPy
- Numba

Through this implementation, there are certain issues found, such as lack of performance improvement when using GPU code compared to CPU coding tools like Numpy.
