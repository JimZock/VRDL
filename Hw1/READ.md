# Bird Images Classification


### [Report](./REPORT.pdf)

This repository is implementation of homework1 for 309351003 Selected Topics in Visual Recognition using Deep Learning course in 2021 fall semester at National Yang Ming Chiao Tung University.

In this homework, we participated a bird image classification challenge hosted on [CodaLab](https://competitions.codalab.org/competitions/35668?secret_key=09789b13-35ec-4928-ac0f-6c86631dda07). 


## Getting the code

You can download a copy of all the files in this repository by cloning this repository:

```
git clone https://github.com/JimZock/VRDL.git
```

## Requirements

coding environment [Google codelab paltform]


## Dataset
This challenge provided a total of 6,033 bird images belonging to 200 bird species.

train dataset :3000 bird images 
test  dataset :3033 bird images

data_preprocessing: image resize(224,224)

## Pre-trained models

using torchvision pretrain model resnet50 this pretrain use imagenet dataset to get better weight 

## Training

Recommended training command: using 4-layer CNN model
use def train() in Hw1_pytorch.ipynb

## Testing
use training finishing model to predict 3033 images label
use def test() in Hw1_pytorch.ipynb to predict and create answer.txt

## Submit the results
Run this command to `zip` your submission file:
```
zip answer.zip answer.txt
```
You can upload `answer.zip` to the challenge. Then you can get your testing score.

## Results

Our model achieves the following performance:



## Citation
If you find our work useful in your project, please cite:

```bibtex
@misc{
    title = {bird_image_classification},
    author = {Chin-Luen Hsu},
    url = {https://github.com/JimZock/VRDL.git},
    year = {2021}
}
```

## Contributing

If you'd like to contribute, or have any suggestions, you can contact us at (mail to: a995782@gmail.com) or open an issue on this GitHub repository.
