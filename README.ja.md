# openai-moderation
[README.ja.md](README.ja.md)に日本語のREADMEがあります。

OpenAIのコンテンツ審査APIにアクセスするためのライブラリです。

## 特徴
- OpenAIのコンテンツ監視モデルを使用して、テキストコンテンツを安全または安全でないと分類する
- 複数のテキスト入力のバッチ処理をサポート
- アプリケーションに簡単に統合できる

## 要件
- Python 3.6 以降
- OpenAI API キー

## 使用方法

### インストール
pipを使ってライブラリをインストールしてください:

```
pip install openai-moderation
```

### 使用例
```python
from openai_moderation import OpenAIModerator

moderator = OpenAIModerator(api_key="your_openai_api_key")

text = "これはモデレーションされるサンプルのテキストです。"
response = moderator.moderate_text(text)

print(response)
```

## ライセンス
このプロジェクトは [MIT License](LICENSE) のもとで公開されています。
