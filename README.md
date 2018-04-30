# Deep Convolutional GAN in Tensorflow - Linux Shell

My project on DCGANs to be run via Linux shell command

Instructions:

git clone https://github.com/RubensZimbres/GAN-Project-2018

cd GAN-Project-2018

python main.py --epoch=5000 --learning_rate=0.0002

Arguments:
--epoch: default=1000
--learning_rate: default=0.0001
--sample_size: default=60
--gen_hidden: # hidden nodes in generator: default=80
--disc_hidden: # hidden nodes in discriminator: default=80

To visualize training in Tensorboard: tensorboard --logdir=/home/your_login/anaconda3/envs/plot_1

<img src=https://github.com/RubensZimbres/GAN-Project-2018/blob/master/GAN_BEST_Linux.png>
