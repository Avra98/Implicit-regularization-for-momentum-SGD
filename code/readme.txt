To generate Figure-1 in manuscript, please run "2D_example.ipynb ". The notebook contains instructions sequentially.

To generate Figure-3 in appendix, please run "2D_Sigmoid.ipynb". The notebook contains instructions sequentially.



To generate Figure-2, 3 and 4 in manuscript, please run the following command:

python train.py --model [model-name] --batch_size [batch-size] --learning_rate [lr] --momentum [beta] --dataset [dataset]



Available options:

model-name= 'resnet18','resnet50','densenet121','wide'
dataset = ''cifar-10','cifar-100'

Dependencies (all latest versions)

1) Numpy
2) Matplotlib
3) Pytorch