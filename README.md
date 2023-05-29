# PacMan
## 実行環境の必要条件
* python >= 3.10.6
* pygame >= 2.4

## ゲームの概要
PacManを十字キーで操作し、さまざまな特殊能力を駆使しながら、ステージ内のすべてのクッキーを食べることでクリアを目指すゲーム。

## ゲームの実装
###共通基本機能
* 音楽の再生
* 主人公キャラクターに関するクラス
* 壁・扉に関するクラス
* クッキー（Block）に関するクラス
* ゴースト（敵）に関するクラス

### 担当追加機能
* 主人公キャラクターをランダムな位置にテレポートさせる機能

### ToDo
- [ ] Tキーを押すことでteleportメソッドを起動
- [ ] ランダムな位置かつ、壁のない場所を指定

### メモ
* クッキーは座標で言うとx,yともに30ごとに置かれている。
* 参考サイトurl:https://github.com/hbokmann/Pacman
