This sample programs compare optimizers in chainer.

The optimizers include SGD, Adam, AdaGrad, MomentumSGD, RMSprop, etc.

First of all, copy train_mnist_opt.py to chainer-*/examples/mnist/ directory.

Next, copy json2csv.py to chainer-*/examples/mnist/result directory.

Then, run `python train_mnist_opt.py -g=* -u=* -e=* -p='SGD'` for SGD.

Finally, `cd result` and run `python json2csv.py -l='log' -c='*.csv'` and you can get csv file.
