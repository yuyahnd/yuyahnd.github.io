# yuyahnd.github.io
My github pages.

## Installation
github から clone します。

```bash
$ git clone https://github.com/yuyahnd/yuyahnd.github.io.git
```

### 環境構築
プロジェクトルートへ移動し、インストールします。
```bash
$ pip install -e .
```

### プロジェクト新規作成
```bash
$ mkdocs new .
```

以下のようなディレクトリが作成されます。
```bash
.
├─ docs/
│  └─ index.md
└─ mkdocs.yml
```

### ローカルサーバー起動
```bash
$ mkdocs serve
```

### build
```bash
$ mkdocs build
```

### Github Pages deploy
```bash
$ mkdocs gh-deploy
```

## License
This repository is licensed under the MIT license. See LICENSE for details.

&copy; 2023 Yuya Honda
