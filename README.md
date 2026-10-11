# NEON STREAM / ネオン・ストリーム / 霓虹极速

A high-speed 3D browser action game made with Three.js.  
日本語 / English / 中文 for in-game language support.

## English

### Game Overview
NEON STREAM is a high-speed 3D action runner that works on smartphones and PCs.
The player automatically runs forward and fires bullets at nearby enemies.
Clear obstacles, defeat enemies, and beat bosses to advance to the next stage.

### Supported In-Game Languages
- Japanese
- English
- Chinese

The language can be changed from the language button.

### Features
- Three.js based 3D action game
- High-speed forward movement
- Works on PCs and smartphones
- Landscape layout for mobile play
- Sound On and Off switch
- Multi-language UI support
- Local save data in the browser
- Many stages
- Many enemy types
- Many boss types
- Pause, retry, title screen, score, best score, and continue from save

### Stage Count
The game contains many stages, including variations in speed, background color, enemy placement, and boss difficulty.

### Bosses
Boss types include:
- GATE-00
- SERPENT-01
- TURRET-02
- SPIDER-03
- SKULL-04
- CORE-05

Boss strength changes depending on the stage.

### Enemy Types
Enemy and obstacle types include:
- Drone
- Wing
- Tank
- Shield
- Spike
- Low Bar
- High Bar
- Orb
- Bomb
- Ghost
- Spinner
- Swarm

Some enemies are destroyed by bullets.  
Some obstacles must be jumped over, slid under, or dashed through.

### How to Run
1. Create an HTML file for the game.
2. Paste the complete game code into the HTML file.
3. Open the HTML file in a modern web browser.
4. On a smartphone, rotate the device to landscape mode.
5. Press the start button on the title screen.

### Network Requirements
This game uses Three.js from a CDN.
Internet access is required unless the Three.js library is saved locally.

### Browser Compatibility
Recommended browsers:
- Chrome
- Edge
- Safari
- Firefox

Older browsers may not support all features.

### Controls

#### PC
- Move left: A key or left arrow key
- Move right: D key or right arrow key
- Jump: W key, Space key, or up arrow key
- Slide: S key or down arrow key
- Dash: Shift key
- Pause: P key or Escape key

#### Smartphone
- Left virtual stick: move left and right
- JUMP button: jump
- SLIDE button: slide
- DASH button: dash

### Gameplay Rules
- Move left and right to avoid obstacles and enemies.
- Jump to pass low obstacles.
- Slide to pass high obstacles.
- Dash to destroy some enemies and obstacles.
- Auto-fire is enabled during normal stage play.
- Defeat bosses to clear a stage.
- After a boss is defeated, the game moves to the next stage.
- Score is added for defeating enemies and completing objectives.
- Best score is saved locally.

### Save Data
Save data is stored locally in the browser.

Saved data may include:
- Current stage
- Current score
- Best score
- Selected language
- Sound setting

Save data can be deleted from the reset button.

### Sound
Sound can be turned on or off from the title screen or game UI.
In some browsers, sound starts after the first user interaction.

### Mobile Notes
The game is designed for landscape screens on smartphones.
If the screen is vertical, the game may display a rotate-device warning.
Virtual buttons and a virtual stick are shown on supported mobile devices.

### Technical Notes
- The game is built as a single HTML file.
- The game uses Three.js.
- The game uses WebGL.
- The game uses localStorage for local saving.
- The game uses the Web Audio API for simple generated sounds.
- No build tool is required.

---

## 日本語

### ゲーム概要
NEON STREAM は、スマートフォンとPCで遊べる Three.js 製のハイスピード 3D アクションゲームです。
プレイヤーは前方へ自動で高速移動し、周囲の敵を自動で攻撃します。
障害物を避け、敵を倒し、ボスを撃破すると次のステージへ進行します。

### ゲーム内対応言語
- 日本語
- 英語
- 中国語

ゲーム内の言語は、言語切り替えボタンから変更できます。

### 機能
- Three.js を使った 3D アクションゲーム
- 高速前方移動
- PCとスマートフォンで動作
- スマホ向け横長画面レイアウト
- サウンド ON / OFF 切り替え
- 多言語UI対応
- ローカルセーブデータ保存
- 多数のステージ
- 多数の敵種類
- 多数のボス種類
- ポーズ、リトライ、タイトル画面、スコア、ハイスコア、続きから遊べる機能

### ステージについて
ゲームには多数のステージが含まれています。
移動速度、背景色、敵配置、ボス難易度などはステージごとに異なります。

### ボス
ボスには以下のような種類があります。
- GATE-00
- SERPENT-01
- TURRET-02
- SPIDER-03
- SKULL-04
- CORE-05

ボスの強さはステージに応じて変化します。

### 敵の種類
敵と障害物には以下のような種類があります。
- ドローン
- ウイング
- タンク
- シールド
- スパイク
- 低い障害物
- 高い障害物
- オブ
- ボム
- ゴースト
- スピナー
- スワーム

一部の敵は弾で倒せます。
一部の障害物はジャンプ、スライド、ダッシュで突破します。

### 遊び方
1. ゲーム用のHTMLファイルを作成します。
2. ゲームの全コードをHTMLファイルに貼り付けます。
3. モダンブラウザでHTMLファイルを開きます。
4. スマートフォンの場合は端末を横向きにします。
5. タイトル画面の開始ボタンを押します。

### ネットワークについて
このゲームは Three.js を CDN 経由で読み込みます。
Three.js をローカルに保存しない場合は、インターネット接続が必要です。

### 推奨ブラウザ
推奨環境:
- Chrome
- Edge
- Safari
- Firefox

古いブラウザでは正しく動作しない場合があります。

### 操作

#### PC
- 左へ移動: Aキー または 左矢印キー
- 右へ移動: Dキー または 右矢印キー
- ジャンプ: Wキー、スペースキー、上矢印キー
- スライド: Sキー または 下矢印キー
- ダッシュ: Shiftキー
- ポーズ: Pキー または Escapeキー

#### スマートフォン
- 左の仮想スティック: 左右移動
- JUMPボタン: ジャンプ
- SLIDEボタン: スライド
- DASHボタン: ダッシュ

### ゲームルール
- 左右に移動して敵や障害物を避けます。
- 低い障害物はジャンプで飛び越えます。
- 高い障害物はスライドで潜り抜けます。
- ダッシュで一部の敵や障害物を破壊できます。
- 通常ステージ中は自動射撃されます。
- ボスを倒すとステージクリアです。
- ボス撃破後は次のステージへ進行します。
- 敵を倒したり目標を達成するとスコアが増えます。
- ハイスコアはローカルに保存されます。

### セーブデータ
セーブデータはブラウザのローカルに保存されます。

保存される情報には以下が含まれる場合があります。
- 現在のステージ
- 現在のスコア
- ハイスコア
- 選択中の言語
- サウンド設定

セーブデータはリセットボタンから削除できます。

### サウンド
サウンドはタイトル画面またはゲーム内UIから ON / OFF できます。
一部のブラウザでは、ユーザー操作後に音声が始まります。

### モバイルに関する注意
このゲームはスマートフォンの横向き画面向けに設計されています。
縦画面の場合、回転を促す表示が出ることがあります。
対応デバイスでは仮想ボタンと仮想スティックが表示されます。

### 技術的なメモ
- ゲームは単一HTMLファイルとして構成されています。
- Three.js を使用しています。
- WebGL を使用しています。
- ローカル保存に localStorage を使用しています。
- Web Audio API で簡易的な効果音を作成しています。
- ビルドツールは不要です。

---

## 中文

### 游戏概述
NEON STREAM 是使用 Three.js 制作的、可在智能手机和电脑上游玩的高速 3D 动作游戏。
玩家会自动向前高速移动，并自动攻击附近的敌人。
躲避障碍、击败敌人并击败 BOSS 后进入下一关。

### 游戏内支持语言
- 日语
- 英语
- 中文

游戏内语言可以通过语言切换按钮更改。

### 功能
- 基于 Three.js 的 3D 动作游戏
- 高速前进玩法
- 支持电脑与智能手机
- 适合手机的横屏界面
- 音效 ON / OFF 开关
- 多语言界面
- 本地存档保存
- 多个关卡
- 多种敌人
- 多种 BOSS
- 暂停、重试、标题界面、分数、最高分、继续游戏功能

### 关卡数量
游戏包含多个关卡。
不同关卡的移动速度、背景颜色、敌人配置和 BOSS 难度会变化。

### BOSS
BOSS 类型包括：
- GATE-00
- SERPENT-01
- TURRET-02
- SPIDER-03
- SKULL-04
- CORE-05

BOSS 强度会根据关卡变化。

### 敌人类型
敌人与障碍物包括：
- 无人机
- 翼兵
- 坦克
- 护盾
- 尖刺
- 低障碍
- 高障碍
- 魔球
- 炸弹
- 幽灵
- 旋转器
- 群蜂

部分敌人可以被子弹击破。
部分障碍需要跳跃、滑铲或冲刺突破。

### 运行方法
1. 创建游戏 HTML 文件。
2. 将完整游戏代码粘贴到 HTML 文件中。
3. 使用现代浏览器打开 HTML 文件。
4. 手机用户请将设备旋转为横屏。
5. 在标题画面按下开始按钮。

### 网络要求
游戏通过 CDN 加载 Three.js。
如果未本地保存 Three.js，则需要联网。

### 推荐浏览器
推荐浏览器：
- Chrome
- Edge
- Safari
- Firefox

较旧浏览器可能无法正常工作。

### 操作方式

#### 电脑
- 向左移动：A键或左方向键
- 向右移动：D键或右方向键
- 跳跃：W键、空格键或上方向键
- 滑铲：S键或下方向键
- 冲刺：Shift键
- 暂停：P键或Escape键

#### 智能手机
- 左侧虚拟摇杆：左右移动
- JUMP按钮：跳跃
- SLIDE按钮：滑铲
- DASH按钮：冲刺

### 游戏规则
- 左右移动躲避敌人和障碍。
- 低障碍使用跳跃。
- 高障碍使用滑铲。
- 部分敌人和障碍可用冲刺破坏。
- 正常关卡中会自动射击。
- 击败 BOSS 即可通关。
- BOSS 被击败后进入下一关。
- 击败敌人或达成目标可获得分数。
- 最高分会保存在本地。

### 存档数据
存档数据会保存在浏览器本地。

可能保存的信息包括：
- 当前关卡
- 当前分数
- 最高分
- 当前语言
- 音效设置

可以通过重置按钮删除存档数据。

### 音效
音效可在标题画面或游戏内界面切换 ON / OFF。
部分浏览器需要在用户操作后才会开始播放声音。

### 移动端说明
本游戏为智能手机横屏设计。
竖屏时可能显示旋转设备提示。
支持设备会显示虚拟按钮与虚拟摇杆。

### 技术说明
- 游戏以单个 HTML 文件运行。
- 使用 Three.js。
- 使用 WebGL。
- 使用 localStorage 保存本地数据。
- 使用 Web Audio API 生成简单音效。
- 不需要构建工具。