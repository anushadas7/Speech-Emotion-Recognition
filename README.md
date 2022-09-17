# <p align = 'center'> Speech Emotion Recognition using CNN, ANN, and SVM</p> 
<p align = 'center'>![image](https://i.imgur.com/kVjepzA.png)</p> 

## Goal
The goal of this project is to detect the emotions produced by the speaker while he or she is speaking. Speech generated in a condition of fear, rage, or delight, for example, becomes loud and quick, with a greater and wider range of pitch, but speech produced in a state of grief or exhaustion is slow and low-pitched. The goal of the presented models is to identify only the emotion in the audio recording that has a higher value. To have a machine classify feelings, various ways have been tried, such as computer vision or text analytics. Our goal in this project is to use pure audio data while considering MFCC.


## Importance
The detection of human emotions via voice and speech patterns has a variety of applications, including improving human-machine interactions. It is also used in a variety of practical applications in fields such as Business Process Outsourcing (BPO) Centers and Call Centers to detect emotion, which is useful for determining a customer's happiness with a product, improving speech interaction, resolving various language ambiguities, and adapting computer systems to an individual's mood and emotion.


## Proposed Solution
The emotion recognition classification models given here are based on a deep learning approach based on CNN, SVM, and MLP classifiers. The key characteristic is that the MFCC, sometimes known as the "spectrum of a spectrum," is the only feature used to train the model. A total of 40 features have been retrieved from each audio file. Each audio file was converted to a floating-point time series to create the functionality. The time series was then converted into an MFCC sequence. The MFCC array has been transposed, and the arithmetic mean on its horizontal axis has been calculated.

![image](https://i.imgur.com/PpA7yKh.png)
