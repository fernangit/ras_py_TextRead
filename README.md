# ras_py_TextRead
text reading by python on the raspberry pie

## HOW TO USE
### ���ʒ���
```
alsamixer
```

### �T�E���h�o�͐�m�F
```
amixer cget numid=3
```

### �T�E���h�o�͐�ݒ�
```
amixer cset numid=3 0
```
(0:����, 1�F�A�i���O, 2�FHDMI)

### OpenJtalk�Ǝ����A�����C���X�g�[��
```
sudo apt-get install open-jtalk open-jtalk-mecab-naist-jdic hts-voice-nitech-jp-atr503-m001
```

### python�v���O����
```
�uOpenJTalk + python �œ��{��e�L�X�g�𔭘b�v���
jtalk.py���C��
```

### �C�ӂ̌��t�𔭘b
```
$ python jtalk.py ����ɂ���
```

### ���W���[������̌Ăяo��
```
import jtalk
jtalk.jtalk(������j
```

## �Q�l���
Raspberry pi�œ��{�ꉹ������(Open JTalk)�������Ă݂�B
https://qiita.com/lutecia16v/items/8d220885082e40ace252
OpenJTalk + python �œ��{��e�L�X�g�𔭘b
https://qiita.com/kkoba84/items/b828229c374a249965a9

## License

