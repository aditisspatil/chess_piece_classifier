# Chess Piece Classifier
Image Classification project using transfer learning.

## Scope
This is an image classifier for chess pieces, which takes an image of chess piece and recognises its name as king, queen, rook, bishop, knight or pawn, along with color as black or white.

## Accuracy
After trying multiple times, I could reach to 93% accuracy for piece name recognition, and 97% accuracy for color recognition.

## Limitations
This classifier might get confused if -
#### 1. Color Specific
The color of the given image is not standard. For instance, some abstract chess sets have Pink-White color combination, while some have Pink-Brown or Pink-Red. Hence, the model might produce incorrect output for the "Pink" piece, depending on the shade of pink.
#### 2. Name Specific
It is esential to feed a clear image. Some pieces, such as bishop-pawn or queen-king, would look same from top angle the corner angle if the image is not clear.
 
## Notes
I have added 2 versions of notebook, to ensure the rendering. 
The bigger verion has image outputs, and hence bigger size, which might be difficult to be redered on GitHub.
The smaller verion only contains image of confusion matrix and demo prediction, and it is loaded properly. Nonetheless, the code and core model is the same.


## Data
I have created the data set myself by taking screenshots of chess sets from google and [chess.com](https://www.chess.com/home).

## Credits
This project is based on [fastai notebook](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb)
I have also referred [Ken Jee's Notebook](https://github.com/PlayingNumbers/ball_image_classifier) to understand usage with Google Colab.
