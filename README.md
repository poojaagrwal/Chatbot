Team Neurons 

- Abhishek Prabhudesai

- Pooja Agarwal

- Rohini Shimpatwar

- Saurabh Aggarwal

We have implemented a Deep learning based chatbot using state-of-the-art Attention  and Encoder-Decoder models based approach. The Cornell movie dataset contains movie titles , dialogs, movie lines, movie conversations etc. which are cleaned and tokenized using tfds SubwordTextEncoder tokenizer. Then they are converted in tf datasets. And passed through attention and encoder decoder layers for neural network learning and prediction.

We have also used AWS S3-Sagemaker-Jupyter pipeline to deploy our model on cloud and having the data stored in S3.

Google colab link - https://colab.research.google.com/drive/1wcWdOaBQ1x5zx1gkUt6zl883zzaVpfFN#scrollTo=JtNhNukNI8pI

Dataset- Cornell Movie Dataset link - https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html

Steps for AWS Pipeline

1) Created s3 and put Cornell Movie Dataset in the bucket to access it.

![](Screenshots_AWS_pipeline/Amazon_S3.png)
![](Screenshots_AWS_pipeline/Amazon_S3_Cornell_Movie_Datasets.png)

2) Created SageMaker instance and uploaded notebook .

![](Screenshots_AWS_pipeline/Amazon_Sagemaker.png)
![](Screenshots_AWS_pipeline/Amazon_Sagemaker_instance.png)
![](Screenshots_AWS_pipeline/Amazon_Sagemaker_instance2.png)

3) Ran the jupyter notebook and implemented the model.

![](Screenshots_AWS_pipeline/Amazon_sagemaker_jupyter_notebook_path.png)
![](Screenshots_AWS_pipeline/Amazon_Jupyter_notebook.png)

4) Tensorboard ScreenShots

![](TensorBoard_Accuracy_Graph.png)
![](TensorBoard_Accuracy_Loss_Graph.png)
