Experiment Results
##
cifar10
baseline 3.40

##
python train_img.py --data cifar10 --lr 1e-4 --ngpu 4 --num_hidden_layers 4
--nblocks 2-2-2-2 --glow False --icnn 1  --save cifar10_baseline2

4.0488

##
python train_img.py --data cifar10 --lr 1e-3 --ngpu 4 --num_hidden_layers 4 
--nblocks 2-2-2-2 --glow False --icnn 2  --save cifar10_baseline3

3.0192 *** epoch 69


##
python train_img.py --data cifar10 --lr 1e-4 --ngpu 4 --num_hidden_layers 4 
--nblocks 2-2-2-2 --glow False --icnn 2  --save cifar10_baseline4
4.8567 4.1483 3.6301 3.2829 3.0698 2.9680 2.9142 2.8817 2.8621 2.8499 
2.8467 2.8415 2.8373 2.8343 2.8335 2.8348 2.8376 2.8420 2.8477 2.8515

2.8335 *** epoch 74

##
python train_img.py --data cifar10 --lr 1e-3 --ngpu 4 --num_hidden_layers 4 
--nblocks 2-2-2-2 --glow False --icnn 3  --save cifar10_baseline5

8.0078

##
python train_img.py --data cifar10 --lr 1e-4 --ngpu 4 --num_hidden_layers 4 
--nblocks 2-2-2-2 --glow False --icnn 3  --save cifar10_baseline6

6.0595

##
python train_img.py --data cifar10 --lr 1e-4 --ngpu 4 --num_hidden_layers 4 
--nblocks 2-2-2-2 --glow False --icnn 3  --save cifar10_baseline6

6.0595


##
minst

##
python train_img.py --data mnist --lr 1e-3 --ngpu 4 --num_hidden_layers 4 
--nblocks 8-8-8 --glow False --icnn 1  --save mnist_baseline1 --batchsize 32

3.3612

##
python train_img.py --data mnist --lr 1e-4 --ngpu 4 --num_hidden_layers 4 
--nblocks 8-8-8 --glow False --icnn 1  --save mnist_baseline2 --batchsize 32

2.9819

##
python train_img.py --data mnist --lr 1e-3 --ngpu 4 --num_hidden_layers 4 
--nblocks 8-8-8 --glow False --icnn 2  --save mnist_baseline3 --batchsize 32

3.7034

##
python train_img.py --data mnist --lr 1e-4 --ngpu 4 --num_hidden_layers 4 
--nblocks 8-8-8 --glow False --icnn 2  --save mnist_baseline4 --batchsize 32

2.5354

##
python train_img.py --data mnist --lr 1e-3 --ngpu 4 --num_hidden_layers 4 
--nblocks 8-8-8 --glow False --icnn 3  --save mnist_baseline5 --batchsize 32

3.2510

##
python train_img.py --data mnist --lr 1e-2 --ngpu 4 --num_hidden_layers 4 
--nblocks 8-8-8 --glow False --icnn 3  --save mnist_baseline6 --batchsize 32

3.8558


##
python train_img.py --data mnist --lr 1e-2 --ngpu 4 --num_hidden_layers 4 
--nblocks 8-8-8 --glow False --icnn 3  --save mnist_baseline5 --batchsize 32

3.8558

##
python train_img.py --data mnist --lr 1e-5 --ngpu 4 --num_hidden_layers 4 --nblocks 8-8-8 --glow False --icnn 2  --save mnist_baseline8 --batchsize 32

2.1553


