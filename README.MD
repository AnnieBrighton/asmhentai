# asmhentai ダウンローダ

## 環境
  MAC(おそらくLinux環境でも動くかと)
  Python 3.6

## 使い方
### 単一指定

     ./asmhentai.py 'https://asmhentai.com/g/245008/'

正常にダウンロードできた場合、カレントディレクトリにzipファイルを作成

     (C95) [榎屋 (eno)] Sultry Altria (FateGrand Order).zip

### 複数指定

ダウンロードしたいリストファイルを作成

sample.txt

    https://asmhentai.com/g/244994/
    https://asmhentai.com/g/244546/

ダウンロード実行

    ./asmhentai.sh sample.txt
