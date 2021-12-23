# reimplementationESRGAN-pytorch

reference paper: https://arxiv.org/abs/1609.04802

I use a different hyperparameters:

```
LEARNING_RATE = 1e-4
START_EPOCHS = 1
NUM_EPOCHS = 100
BATCH_SIZE = 4
NUM_WORKERS = 4
HIGH_RES = 256
LOW_RES = HIGH_RES // 4
IMG_CHANNELS = 3
```

## Result

#### Low Resolution Image

![1](asset/LR_images/0803x4.png)

![2](asset/LR_images/0809x4.png)

![3](asset/LR_images/0810x4.png)

![4](asset/LR_images/0842x4.png)

![5](asset/LR_images/0866x4.png)

#### High Resolution result

![1](asset/HR_images/0803x4.png)

![2](asset/HR_images/0809x4.png)

![3](asset/HR_images/0810x4.png)

![4](asset/HR_images/0842x4.png)

![5](asset/HR_images/0866x4.png)

#### Comparison

![7](asset/result/ESRGAN_result_1.png)

## License

for the code it's MIT license but for the weight it's not for commercial just research purpose only because I train on DIV2K datasets
