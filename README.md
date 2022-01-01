# Skript

## What is Skript
[Skript v2.6](https://github.com/SkriptLang/Skript/releases/tag/2.6)<br>

## scripts1

[これのSkriptまとめ](https://twitter.com/faa0311/status/1472424668959490050)<br>

> ### [custom-enchant-excavator](/scripts1/custom-enchant-excavator.sk)<br>
> Multiple block excavation / 複数のブロックを掘削するエンチャント<br>
> For Essentials / Essentialsの場合<br>
> ` /essentials:lore add &6土採掘 I `<br>
> ` /essentials:lore add &e砂採掘 II `<br>
> ` /essentials:lore add &7砂利採掘 VII `<br>

> ### [custom-enchant-miner](/scripts1/custom-enchant-miner.sk)<br>
> Multiple block mining / 複数のブロックを採掘するエンチャント<br>
> For Essentials / Essentialsの場合<br>
> ` /essentials:lore add &7石採鉱 I `<br>
> ` /essentials:lore add &c花崗岩採鉱 II `<br>
> ` /essentials:lore add &f閃緑岩採鉱 VII `<br>

> ### [drop](/scripts1/drop.sk)<br>
> 最初にスポーンするときに使うコマンド<br>
> ` /start `<br>

> ### [fast-furnaces](/scripts1/fast-furnaces.sk)<br>
> x20 furnaces / 20倍のかまど<br>
> #### Addon
> - [SkBee v1.14.0](https://github.com/ShaneBeee/SkBee/releases/tag/1.14.0)

> ### [fast-reload](/scripts1/fast-reload.sk)<br>
> 開発用の素早くSkriptをリロードするコマンド<br>
> ` /sk `<br>

> ### [greek-number-converter](/scripts1/greek-number-converter.sk)<br>
> ギリシャ文字を変換する関数<br>
> ` greekNumberConverter(i: number) :: text `<br>

> ### [money](/scripts1/money.sk)<br>
> お金関係とか 1ダイヤ=1通貨 ゲーム内の経験値と同期<br>

> ### [move-worldborder](/scripts1/move-worldborder.sk)<br>
> ワールドボーダーを移動させる<br>

> ### [save](/scripts1/save.sk)<br>
> 帰還するコマンド<br>
> ` /save `<br>

> ### [teleportStop](/scripts1/teleportStop.sk)<br>
> テレポートするために停止させる<br>
> ` teleportStop(i: number, player: player, command:text) `<br>


> ### [villager-item-shop](/scripts1/villager-item-shop.sk)<br>
> 村人のアイテムショップ<br>

> ### [villager-tool-shop](/scripts1/villager-tool-shop.sk)<br>
> 村人の装備ショップ<br>
[custom-enchant-excavator](/scripts1/custom-enchant-excavator.sk)や
[custom-enchant-miner](/scripts1/custom-enchant-miner.sk)を販売する村人

> ### [world-guard](/scripts1/world-guard.sk)<br>
> ワールドを破壊や設置から守る<br>

## scripts2

けむちゃんサーバーv2に使用しているSkriptまとめ

> ### [cmd](/scripts2/cmd.sk)<br>
> 単体で動作する便利コマンドとか<br>
> プレイヤー全員のバージョンを取得する<br>
> ` /player version `<br>
> #### Plugin
> - [ViaVersion v4.1.1](https://github.com/ViaVersion/ViaVersion/releases/tag/4.1.1)
> - [PlaceholderAPI v2.11.1](https://github.com/PlaceholderAPI/PlaceholderAPI/releases/tag/2.11.1)

> ### [fast-reload](/scripts2/fast-reload.sk)<br>
> 開発用の素早くSkriptをリロードするコマンド<br>
> ` /sk `<br>

> ### [guard](/scripts2/guard.sk)<br>
> ワールドを破壊や設置、mobのスポーンから守る<br>

> ### [is_world](/scripts2/is_world.sk)<br>
> ワールドを判定するための関数<br>
> ` is_build_world(world: world) :: boolean `<br>
> ` is_player_world(world: world) :: boolean `<br>
> ` is_resource_world(world: world) :: boolean `<br>
> ` is_other_world(world: world) :: boolean `<br>

> ### [join](/scripts2/join.sk)<br>
> 参加したときの判定<br>
> ホワイトリストなど<br>

> ### [menu](/scripts2/menu.sk)<br>
> コマンドメニューを作る<br>
> 頭のボタン、プレイヤーの選択GUI、テキスト入力対応<br>
> permission: `yuki.menu`<br>
>
> メニュー表示<br>
> ` /menu `<br>
>
> 内部で使用しているプレイヤーの選択GUI<br>
> ` /select player <text>`<br>
> 例: ` /select player ban `<br>
>
> 内部で使用しているテキスト入力<br>
> ` /select chat <text> <text>`<br>
> 例: ` /select chat say 送信する文字を入力して下さい`<br>


> ### [teleportTimer](/scripts2/teleportTimer.sk)<br>
> テレポートするために停止させる<br>
> ` stopTimer(i: number, player: player, name: text, command: text) `<br>
> 例: ` stopTimer(3, player, "テレポート", "/tp %player% ~ 120 ~") `<br>

> ### [world](/scripts2/world.sk)<br>
> ロビーワールドのテレポートとか<br>
