# Image_Caption_Generator_Using_LSTM_and_CNN

<p align="center">
    <a href="https://github.com/Sabareesh000/Lock_Unlock_A_Computer_Using_RFID"><img src="image.png" alt="Logo" border="0"></a>
    <br>A Deep Learning Project that allows you to Generate Captions based on the Image Provided.
</p>

## Table of Contents

-   [Motivation](#Motivation)
-   [Installation](#Installation)
-   [Contributing](#Contributing)
-   [License](#License)

## Motivation
The project's core objective revolves around automating the process of generating descriptive captions for images, condensing a multi-faceted task into a single streamlined solution. By leveraging state-of-the-art technologies such as computer vision and natural language processing, the project aims to provide succinct and informative captions for images. 

This simplification not only enhances the accessibility of visual content, particularly for individuals with visual impairments, but also empowers content creators to efficiently add context to their images. The resulting captions serve as bridges between the visual and textual realms, enriching user experiences and enabling improved content discovery through search engine optimization (SEO). In essence, the project embodies the convergence of innovative technology and practical utility, reshaping the way we perceive and engage with images in a seamless, one-line process.

By embarking on this project, we are embracing cutting-edge technology, bridging gaps in accessibility, and pushing the boundaries of content creation and communication in an increasingly visual world.

## Installation

Firstly, clone the repository using,

<pre>
git clone https://github.com/sabareeshreddy/Image_Caption_Generator_Using_LSTM_and_CNN

</pre>

Get the Dataset from Here!
<pre>
https://www.kaggle.com/datasets/adityajn105/flickr8k

</pre>


Once you have the source code and the dataset in the repo, create a virtual environment using the following command,
`python3 -m venv venv`

Enter the virtual environment and install dependencies using `pip install -r requirements.txt`.

Once all the dependencies installation is completed, You need to start running the cells one by one.

The major step in the process is `Feature extraction`. This can take a few minutes of time, As it extracts the features from the Entire Dataset which contains around 8K Images.

Specify the Working Directory path to save the Extracted Features `Features.pkl` for later use.

After Successfully following the steps, then we may encounter the major step called the `Saving Model`.

Once Again Specify the Working Directory for Saving the Best Model. Will be Saved in the form of `Model.h5` format.

Hurray! The major part of the process is almost done!

In order to run the project once again at a later point in time, we need to make sure that all the variables are saved before closing the project or Exiting Kernal.

It will Store all the Temporary variables so that we call recall them and execute them at a later point in time.

## Contributing

To contribute to the project, fork the repository, create a new branch, and send us a pull request.

Also, thanks for contributing to Open-source! 💖


## License

Text_Summarization is under The MIT License. Read the [LICENSE](https://github.com/sabareeshreddy/Text_Summarizer/blob/main/LICENSE) file for more information.



