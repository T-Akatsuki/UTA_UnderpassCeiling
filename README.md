# UTA_UnderpassCeilingプラグイン

## ■概要 : Overview
指定したリージョンIDを設定したタイルマップの下をくぐり抜けられるようするRPGツクールMV用プラグインです。  
天井裏を通過できる隠し通路などを作成したい場合に特に有効です。  

Local版、Web版(Canvasモード、WebGLモード)どちらにも対応しています。

## ■利用方法 : Usage
ご自身のプロジェクトにUTA_UnderpassCeiling.jsを配置し、プラグインの有効化を行って下さい。  

Underpass Region IDで指定されたリージョンIDをくぐり抜けさせるタイルに設定して下さい。  
天井タイルをくぐり抜けられるようにすると、天井タイルを自由に移動できる状態になってしまうので、  
くぐり抜けられるようにした道を挟むように通行不可リージョン(Not Passable Region IDで設定したリージョン)を設定して下さい。  

詳しい利用方法はWebサイトに掲載しておりますのでご一読下さい。  
https://www.utakata-no-yume.net/gallery/rpgmv/plugin/underpass_ceiling/

## ■プラグインパラメーター : Plugin Parameters
### Underpass Region ID
くぐり抜けられるタイルマップに付与するリージョンIDの定義。

### Not Passable Region ID
通行禁止にするリージョンIDの定義。

## ■プラグインコマンド : Plugin Commands
プラグインコマンドはありません。

## ■更新履歴 : Change Log
### ver 1.0.0 (2018.08.25)
初版。

## ■ライセンス/利用規約 : License
本プラグインは[MIT License](LICENSE)です。  
商用/非商用問わずにご利用いただけます。

## ■連絡先 : Content Information

|  |  |
|:---:|:---|
| Author | 赤月 智平(T.Akatsuki) |
| WebSite | https://www.utakata-no-yume.net |
| Twitter | [@T_Akatsuki](https://twitter.com/t_akatsuki) |
| GitHub | https://github.com/T-Akatsuki |
