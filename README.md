Quantization Exercise

You are given a vector, a quantization grid, and an optimization metric. Your task is to write Python code to solve the optimization problem and determine the quantized weights.

Vector: v = [3.2, -1.4, 2.5, -0.9, 1.8, -3.7, 0.0, 4.0, 2.2, -1.3]

Quantization grid (bits): Assume you have 3-bit quantization, which allows for 8 distinct values in a uniform quantization grid, distributed evenly from -4 to 4.

Optimization Metric: Use the L2 norm between the original vector and the quantized vector as the optimization metric.

Output: The goal is to quantize the given vector such that each element in the vector is replaced by one of the quantization levels, minimizing the optimization metric.
