# The Python3 version of HANCD/HANT
This is an unofficial implementation based on the model in Lu Cheng's [Modeling Temporal Patterns of Cyberbullying Detection with Hierarchical Attention Networks](https://github.com/GitHubLuCheng/Modeling-Temporal-Patterns-of-Cyberbullying-Detection)([Paper](https://dl.acm.org/doi/10.1145/3441141))

## Training
1.Download the pretrained word2vec 400M Twitter model from [here](https://github.com/loretoparisi/word2vec-twitter)

2.Download the instagram dataset from [here](https://drive.google.com/file/d/1ZiHMMjZ0HDcFkFhJhIvq4A4qUewikwkl/view?usp=sharing)

3.Run
```
pip install -r requirements.txt
```
then
```
python HANCD_word2vec.py
# or
python HANT.py
```