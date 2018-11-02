# prichan-items-scraper
「キラッとプリ☆チャン」のアーケードゲームの[アイテムリスト](https://prichan.jp/items/index.html)からアイテムの情報を収集するPythonのScrapyのスクリプトです。

Python scrapy scripts to gather the information of [Kiratto Pri☆Chan's arcade game items](https://prichan.jp/items/).

## fork元からの変更点とか
- 新しいウェブページの書式でスクレイピングが動かなかったので修正しました。
- travisで定期的にアイテムをスクレイピングするようにしました。  
うまく動けば毎週更新されるはずです。  
最新のcsvデータのurlは[items_url](https://github.com/KeikaChan/prichan-items-scraper/blob/master/items_url)の中に入っています。  

## ライセンス (License)
- [GNU General Public License v3](LICENSE)
