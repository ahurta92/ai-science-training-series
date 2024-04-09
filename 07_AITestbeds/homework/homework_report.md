#
AI acelerator homework report

1. Running BERT of SambaNova using --ntask 8 versus --ntask 16

In this case ntask defines the number of copies that are distributed
accross the RPUs.  Comparing the performance I mainly saw that with 
ntask 8 the training time was increased compared to ntask 16.

2. Running MNIST example on graphcore and adusting the hyperparameters.

In the first case we have the following parameters:

learning rate: 0.03
epochs: 10
batch size: 8
test_batch_size: 80

For testing I will increase.

3. Running BERT example on Cerebras 

Run BERT example with different batch sizes like 512, 2048 and observe the performance difference.

So I started running the first example but after running the launch command I waited 
for some time. I then moved on the next example beforef finishing.  

4. Running on Groq

I first tried to run on Groq but I had some issues with the installation.  I then lost
motivation so I decided to move on.  


Overall, I had difficulty with this homework.  While I was able to log into each machine 
it was difficult to smoothly run the examples.  I need more time look at all of the scripts and 
to get a better understanding of the hardware.  

