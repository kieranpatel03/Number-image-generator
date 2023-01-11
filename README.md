# Number-image-generator
Will use a generative adversarial network to generate images of numbers using the MNIST dataset

A reconstructor network was added to prevent mode collapse which is where the generated data will produce images in only a small part of the distribution. The reconstructor network will map the generated and sample images back to a normal distribution. 
