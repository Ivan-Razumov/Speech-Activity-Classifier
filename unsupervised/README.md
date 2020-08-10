# Unsupervised solution
## rnn-autoencoder notebook contains training of rnn autoencoder
## in rnn-encoder-latent-clustering-pca we work on latent features  encoded by model
## supervised solution based on rnn autoencoder latents gave us  85 - 90% accuracy
## unsupervised solution based on rnn autoencoder gave us about 55% accuracy (kmeans)
## unsupervised solution based on average-pooling from stft gave about 80-85% accuracy on supervised and around 50 on unsupervised  

# Approaches that were not so good
## VAE on stft images gave us about 55% accuracy on CLASSIFICATION
## CNN+RNN autoencoder latent features gave about 44% accuracy on CLASSIFICATION
## low classification score tells us it is hard even to devide set by a giperplane in the latent space

