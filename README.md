# GANs_on_MNIST_Torch
Generative Adversarial Networks on MNIST database using PyTorch.


# Dataset
MNIST : Handwritten Digits.

# Results

## Generated Images Through Training

Epoch 1           |  Epoch 10
:-------------------------:|:-------------------------:
![Epoch 1](./fake_mnist/sample_0.png)  |  ![Epoch 10](./fake_mnist/sample_9.png)

Epoch  50           |  Epoch 200
:-------------------------:|:-------------------------:
![Epoch 50](./fake_mnist/sample_49.png)  |  ![Epoch 200](./fake_mnist/sample_199.png)

## Discrimnator and Generator losses

Generator           |  Discriminator
:-------------------------:|:-------------------------:
![loss of generator](./losses_mnist/g_loss.png)  |  ![loss of discriminator](./losses_mnist/d_loss.png)

## Dicriminator's mean prediction on real and on generated data

Real Images           |  Fake Images
:-------------------------:|:-------------------------:
![discrimantor's mean prediciton on real images](./losses_mnist/d_on_fake.png)  |  ![discrimantor's mean prediciton on fake images](./losses_mnist/d_on_real.png)

