# Simple NodeJS voice recognition example using Mozilla DeepSpeech

Install [DeepSpeech](https://github.com/mozilla/DeepSpeech)

```
pip3 install deepspeech
```

Download the pre-trained model (1.8GB):

```
wget https://github.com/mozilla/DeepSpeech/releases/download/v0.4.1/deepspeech-0.4.1-models.tar.gz
tar xvfz deepspeech-0.4.1-models.tar.gz
```

Install Sox (for .wav file loading):

```
brew install sox
```

Install NPM dependencies:

```
npm install
```

Run:

```
node index.js
```

Result should be something like:

```
2019-02-22 13:13:44.271363: I tensorflow/core/platform/cpu_feature_guard.cc:141] Your CPU supports instructions that this TensorFlow binary was not compiled to use: AVX2 FMA
audio length 6.0445625000000005
result: queen e sex to de two
```
