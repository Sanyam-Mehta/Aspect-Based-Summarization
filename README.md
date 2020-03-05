# Aspect-Based-Summarization
This is a PyTorch implementation of the paper "Inducing Document Structure for Aspect-Based Summarization."
The work depends on the Pytorch implemention of Pointer Generator Network by Atul Kumar (https://github.com/atulkum/pointer_summarizer).  The changes made in the code are as follows:-
1.) batcher.py is updated to include the information about the aspect
2.) model.py is updated to make the required changes as given in the paper "Inducing Document Structure for Aspect-Based Summarization"
3.) train.py is updated to include aspect ids and then pass them to the model at training time
4.) config is updated to set the encoder steps as 2000, keeping all the other things as the same 
5.) train_util.py is updated so that they can return a list of aspects

To obtain the dataset, follow the instructions given at https://github.com/ColiLea/aspect_based_summarization

I am an undergrad student and I do not have enough resources to run this code. To train the model I am using Google Colab, which is a litlle bit of a difficult task given the time it requires to train the pointer generator network. I'll share the results as soon as I get them and update the readme file accordingly.

Feel free to open an issue if you want to suggest something.
