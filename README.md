# Mental-health-Chatbot 
This is an AI-powered bot designed to provide emotional support and assistance to individuals struggling with mental health issues. 
It can help individuals access mental health resources, offer guidance and support. 
With the integration of Language translation, this chatbot will be very efficient as it will be able to break the language barriers. 

The creation of a chatbot capable of language translation, holds transformative potential, acting as a catalyst in overcoming language barriers for effective communication and information exchange. 
Its impact spans diverse sectors, including: healthcare, commerce, and governance etc. offering a versatile solution to bridge linguistic gaps.

https://codeaxe.co.ke/multilingobot/
# How to run it?

First step is to download the models from the link <a href="https://drive.google.com/drive/folders/1ybwgK1XNG1wd8As0m9vjMdQfHmD6E9uk?usp=sharing"> MODEL </a> add the model in the root/model project directory.

The following instructions were tested on the Windows and Linux with Python 3.8.

1. Clone this repository

```
git clone https://github.com/MarlonHenq/Mental-health-Chatbot
```
```
cd Mental-health-Chatbot/
```

2. Create and activate virtual environment 

```
python -m venv venv
```
on Linux system
```
source venv/bin/activate
```
on Windows system
```
.\venv\Scripts\activate.bat
```
3. Install requirements

```
pip install  -r requirements.txt
```

4. Install sentencepiece

```
pip install sentencepiece
```

5. Install pytorch

```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
```

6. Install spacy

```
pip3 install spacy
```

7. Install spacy language model

```
python -m spacy download en_core_web_sm // for english
python -m spacy download pt_core_news_sm // for portuguese
```

8. Install flask

```
pip install flask
```

9. Install tensorflow

```
pip install tensorflow
```

10. Install sacremoses

```
pip install sacremoses
```


11. Run the 
```
flask --app app --debug run
```

# Important for training the model

If you dont have a GPU, you can use the CPU.

Install tensorflow for CPU

```
pip install tensorflow-cpu
```

And change the global variable on your computer

```
export CUDA_VISIBLE_DEVICES=""
```

# For training the model

View the [Datasets Folder](Datasets) for more information about the data.

![image](https://user-images.githubusercontent.com/62094358/221975328-2c9500a6-d551-4704-8544-e60e449bcdda.png)
