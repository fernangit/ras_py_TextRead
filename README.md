# ras_py_TextRead
text reading by python on the raspberry pie

## HOW TO USE
### 音量調節
```
alsamixer
```

### サウンド出力先確認
```
amixer cget numid=3
```

### サウンド出力先設定
```
amixer cset numid=3 0
```
(0:自動, 1：アナログ, 2：HDMI)

### OpenJtalkと辞書、音声インストール
```
sudo apt-get install open-jtalk open-jtalk-mecab-naist-jdic hts-voice-nitech-jp-atr503-m001
```

### pythonプログラム
```
「OpenJTalk + python で日本語テキストを発話」より
jtalk.pyを修正
```

### 任意の言葉を発話
```
$ python jtalk.py こんにちは
```

### モジュールからの呼び出し
```
import jtalk
jtalk.jtalk(文字列）
```

## 参考情報
Raspberry piで日本語音声合成(Open JTalk)を試してみる。
https://qiita.com/lutecia16v/items/8d220885082e40ace252
OpenJTalk + python で日本語テキストを発話
https://qiita.com/kkoba84/items/b828229c374a249965a9

## License

