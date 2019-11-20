# A mute lip-reading approach

**This is a project description draft only.**

This project is an attempt to perform lip reading.

We got inspired from [this video](https://www.youtube.com/watch?v=28U6EwfKois) and wanted to assess the quality of this work by doing an indipendent implementation work.

## Project structure
Fundamentally, it consists of using a CNN classifier to recognize phonems from the lip position in every frame of a 25fps video. Phonem extraction for the English language used during training is offered by [Gentle](https://lowerquality.com/gentle/).

As an attempt to improve the efficiency of the model presented in the video, we are planning of using boosting techniques to achieve better accuracy and use NLP techniques such as Hidden Markov Chain to take advantage of context information and grammar.

If everything goes well, we might as well make a white paper explaining our approach and results.

## Languages and Libraries

This project is going to be built on top of C++ and Python and some ML/NLP libraries, namely OpenCV, Tensorflow and NLTK.

## Hall of fame

- Enrico Trombetta aka erolm-a (`trombetta dot enricom at protonmail dot com`)

- Marianna Marcelline

## Dataset

Currently reviewed datasets include:

- [ ] BBC documentaries.
- [ ] Theatre performances.
- [ ] The bee movie :P .

Because we believe in result replicability, we will try to share the datasets when possible.

## License

This project is released under the Mozilla Public Licence. Everybody is welcome to make Pull Requests or fork your own version. 
