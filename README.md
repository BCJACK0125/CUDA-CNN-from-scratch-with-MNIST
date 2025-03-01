# CUDA-CNN-from-scratch
從零實作出CNN (以MNIST為例)

## Execution

nvcc -lcuda -lcublas main.cu layer.cu -o CUDA_CNN -arch=compute_50 -Wno-deprecated-gpu-targets

./CUDA_CNN

## Flow Diagram
### Feedforward 
![image](https://github.com/user-attachments/assets/ff048cd0-98fe-4318-9799-2c7da3c89921)

### Backpropagation
![image](https://github.com/user-attachments/assets/e32de57f-896d-4e1b-92c0-4876bda30e53)
