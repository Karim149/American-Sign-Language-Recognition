# American-Sign-Language-Recognition
Built a deep learning system to recognize American Sign Language (ASL) letters from image sequences. using CNNs, and correct predicted words using natural language processing.                         
This project recognizes American Sign Language (ASL) alphabet letters from image sequence of hand gesture  using a Convolutional Neural Network (CNN). from individual letters, it constructs words and corrects them using a basic NLP spell-checker.

##  Features
- Classifies ASL letters (A–Z, excluding J)
- Predicts full words from sequences of hand gestures
- Corrects word outputs using NLP spell correction
- Visual display of predictions

##  Technologies Used
- Python
- TensorFlow / Keras
- Computer Vision
- Natural Language Processing (SpellChecker)
- Matplotlib / PIL


##  How it Works
1. Preprocesses grayscale hand gesture images
2. Classifies letters using CNN
3. Combines predicted letters into words
4. Applies spell correction for accurate output

##  Example Output
> Input Letters: T, E, S, T  
> Output Word: `TSET`  
> Corrected Word: `TEST`
