この設定ファイルは、Hyprlandでのキー操作（keybind）の動作を定義しています。以下は、記述されている全てのキー操作の動作を説明します。

---

### 基本的なキー操作（Default Keybinds）
- **`CTRL + ALT + Delete`**  
  Hyprlandを終了する。

- **`SUPER + Q`**  
  アクティブなウィンドウを終了する。

- **`SUPER + F`**  
  フルスクリーンモードを切り替える。

- **`SUPER + SHIFT + Q`**  
  `$scriptsDir/KillActiveProcess.sh`を実行。

- **`SUPER + SHIFT + F`**  
  ウィンドウのフローティング状態を切り替える。

- **`SUPER + ALT + F`**  
  全てのウィンドウをフローティング状態に切り替える。

- **`CTRL + ALT + L`**  
  `$scriptsDir/LockScreen.sh`を実行（画面ロック）。

- **`CTRL + ALT + P`**  
  `$scriptsDir/Wlogout.sh`を実行（ログアウトメニューを表示）。

---

### ユーティリティ・拡張機能
- **`SUPER + H`**  
  `$scriptsDir/KeyHints.sh`を実行（ヘルプを表示）。

- **`SUPER + ALT + R`**  
  `$scriptsDir/Refresh.sh`を実行（WaybarやRofiなどをリフレッシュ）。

- **`SUPER + ALT + E`**  
  `$scriptsDir/RofiEmoji.sh`を実行（絵文字選択）。

- **`SUPER + S`**  
  `$scriptsDir/RofiSearch.sh`を実行（Google検索）。

- **`SUPER + SHIFT + B`**  
  `$scriptsDir/ChangeBlur.sh`を実行（ぼかし設定の切り替え）。

- **`SUPER + SHIFT + G`**  
  `$scriptsDir/GameMode.sh`を実行（アニメーションのON/OFF切り替え）。

- **`SUPER + ALT + L`**  
  `$scriptsDir/ChangeLayout.sh`を実行（レイアウトの切り替え）。

- **`SUPER + ALT + V`**  
  `$scriptsDir/ClipManager.sh`を実行（クリップボードマネージャ）。

- **`SUPER + SHIFT + N`**  
  `swaync-client`をトグル（通知パネル）。

---

### ユーザースクリプト関連
- **`SUPER + E`**  
  `$UserScripts/QuickEdit.sh`を実行（Hyprland設定の簡易編集）。

- **`SUPER + SHIFT + M`**  
  `$UserScripts/RofiBeats.sh`を実行（音楽再生）。

- **`SUPER + W`**  
  `$UserScripts/WallpaperSelect.sh`を実行（壁紙選択）。

- **`SUPER + SHIFT + W`**  
  `$UserScripts/WallpaperEffects.sh`を実行（壁紙エフェクト変更）。

- **`CTRL + ALT + W`**  
  `$UserScripts/WallpaperRandom.sh`を実行（ランダム壁紙）。

- **`SUPER + ALT + O`**  
  アクティブウィンドウの透明度を切り替える。

---

### Waybar関連
- **`SUPER + B`**  
  `waybar`をトグル（表示/非表示）。

- **`SUPER + CTRL + B`**  
  `$scriptsDir/WaybarStyles.sh`を実行（Waybarのスタイル変更）。

- **`SUPER + ALT + B`**  
  `$scriptsDir/WaybarLayout.sh`を実行（Waybarレイアウト変更）。

---

### レイアウト関連（Master/Dwindle）
- **`SUPER + CTRL + D`**  
  マスターレイアウトからウィンドウを削除。

- **`SUPER + I`**  
  マスターレイアウトにウィンドウを追加。

- **`SUPER + J`**  
  ウィンドウを次に移動。

- **`SUPER + K`**  
  ウィンドウを前に移動。

- **`SUPER + M`**  
  スプリット比率を`0.3`に設定。

- **`SUPER + P`**  
  仮想ウィンドウ（pseudo）をトグル。

- **`SUPER + CTRL + Return`**  
  マスターウィンドウと現在のウィンドウを入れ替える。

---

### グループ操作
- **`SUPER + G`**  
  ウィンドウグループを切り替える。

- **`SUPER + CTRL + Tab`**  
  グループ内でフォーカスを移動。

---

### ウィンドウ操作
- **`ALT + Tab`**  
  次のウィンドウに切り替え。

- **`ALT + Tab`**  
  フローティングウィンドウを前面に持ってくる。

---

### 音量・メディア操作
- 音量アップ/ダウン、ミュート、再生・停止、次/前のトラック操作が可能（特殊キー）。

---

### スクリーンショット関連
- **`SUPER + Print`**  
  画面全体のスクリーンショットを即座に撮影。

- **`SUPER + SHIFT + Print`**  
  範囲選択してスクリーンショットを撮影。

- **`ALT + Print`**  
  アクティブウィンドウを撮影。

---

### ウィンドウのリサイズ
- **`SUPER + SHIFT + 矢印キー`**  
  アクティブウィンドウをリサイズ（上下左右）。

---

### ウィンドウの移動
- **`SUPER + CTRL + 矢印キー`**  
  アクティブウィンドウを移動。

---

### ワークスペース関連
- **`SUPER + Tab`**  
  次のワークスペースに移動。

- **`SUPER + SHIFT + Tab`**  
  前のワークスペースに移動。

- **`SUPER + [1-9]`**  
  ワークスペースを切り替え。

- **`SUPER + SHIFT + [1-9]`**  
  ウィンドウを指定のワークスペースに移動。

---

64 super
65 super shift
12 ctrl alt

