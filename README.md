# mac_setting
## ソフト
- [Rectangle](https://github.com/rxhanson/Rectangle)<br>
    ウインドウ操作便利にするやつ<br>
    `RectangleConfig.json`をインポート<br>
- [MonitorControl](https://github.com/MonitorControl/MonitorControl)<br>
    外部ディスプレイ使う時便利なやつ<br>
- [Mos](https://github.com/Caldis/Mos)<br>
    マウス加速度無効&スクロール方向逆
- [Karabiner](https://github.com/pqrs-org/Karabiner-Elements)<br>
    マウスのサイドボタン使えるようにするやつ<br>
    [参考](https://www.unlogue.com/mac-sidebutton/)
## Dock表示高速化
```
defaults write com.apple.dock autohide-delay -float 0; defaults write com.apple.dock autohide-time-modifier -int 1 ;killall Dock
```
