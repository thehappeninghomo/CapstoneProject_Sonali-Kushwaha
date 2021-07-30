# CapstoneProject_Sonali-Kushwaha

## Handwritten-Digit-Recognition(based on CNN)

### To run the code:
1. Clone the repository on your computer ``` git clone https://github.com/thehappeninghomo/CapstoneProject_Sonali-Kushwaha.git```.
2. Make sure you have proper environment containing required libraries. 
3. Two jupyter notebooks are there:-
Training model: ```trainingModel.ipynb``` (It contains evaluation using MNIST test dataset).
Testing model: ```testingModel.ipynb``` (It contains evaluation using MS-Paint[not interactive]).
4. Model has been saved as ```HAMARA_PYARA_MODEL.keras```.
5. While giving input from MS-Paint, you need to specify the image name manually. Two examples are given as ```something.png```(current I/P) which contains ```7``` and ```something2.png``` which contains ```2```. It's advisable to change image name in both ```testModel.py``` and ```testingModel.ipynb```.
6. For drawing image, Black background and white crayon brush would do. 

### For Your Ease: A python file named ```testModel.py``` contains similar code as that of the ```testingModel.ipynb``` and is executable from command line. 

### Limitations:
1. This model is trained only for digit recognition. So, it won't be giving desired results for othe character inputs.
2. Manual input of the image name is needed.
3. It may or may not work for filenames with extensions other than ```.png```.
