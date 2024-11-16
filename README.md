# fck-primehome
唐突にサーバーを規制した日本向けのIPTV Primehomeを強制的に復活させて使用する抜け道を見つけました。

ソースコードを公開すると対策される可能性があるのでexe形式と難読化したpythonスクリプトのみを配布します。

見れるチャンネルはあなたの環境によって大きく異なりますが、4~6割程度のチャンネルを復活させました。

つまりこのスクリプトを使っても、誰かの環境ではTokyoMXは視聴できるけど、あなたの環境ではTokyoMXが視聴できない可能性があります。

注意：※IPアドレスが代わると見れなくなります。その際は再度にスクリプトを実行して下さい。

全部のprimehomeチャンネルが見える訳ではありませんがこのスクリプトを実行すれば復活します。

生成したindex.m3u8をVLCで読み込むだけです:)

### 使い方

Linux 
```bash
pip install requests beautifulsoup4
git clone https://github.com/ERM073/fck-primehome/
cd fck-primehome
```



Windows

https://github.com/ERM073/fck-primehome/releases/latest

からfck.exeをインストールして実行
