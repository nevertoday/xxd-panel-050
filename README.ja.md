<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 050 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 050

### 一枚の写真から、その場所だけの空色トラベル・ビジュアルへ

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D5898C?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-6FA4B7?style=flat-square)](#)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 専用トラベルシーン · エアリーブルー · ミニマルなフラットベクター · 編集的余白 · 一枚ごとの固有性

元写真の最も識別しやすい主題と物語的な関係を、その写真だけの上質なトラベル・ビジュアルへ変換します。主役は一つ、根拠のある環境要素は2〜4個、余白は静かに、色は軽やかな青を中心に。都市名だけを差し替える汎用テンプレートではありません。

## 美的ロジック

```text
主題・姿勢・物語関係を固定 → 固有の手掛かりを3つ残す → 主視覚を一つ選ぶ → 元写真から環境の証拠を2〜4個抽出 → テンプレートでなく主題に沿って再構成 → 空気感のある青いフラットベクターで統一 → 静かな余白を残す → 題名とタグラインを場面のアイデンティティにする
```

無関係な写真へ差し替えても識別性、環境要素、空間秩序、色の関係、文案が変わらないなら、この Panel には属しません。

## ビジュアル契約

- 元写真固有の手掛かりを最低3つ保ち、主題を一般的なアイコンにしません。
- 焦点は一つ。環境要素は元写真に根拠のある2〜4個だけ。人物が必要なら3〜6人の小さな存在として溶け込ませます。
- 場面は元写真に決めさせ、無関係なランドマーク、都市名テンプレート、絵葉書公式を使いません。
- 日本の文具、上質なステッカーイラスト、現代的なトラベル・ブランディングの感覚を用い、単純な幾何形、柔らかな輪郭、統一線幅、平塗り、抑えた細部、十分な余白で構成します。
- パウダー、霧、空、空気感のある寒色系ブルーを中心に、アイボリー、クリーム、淡いベージュ、柔らかな灰緑、建築的中間色で整えます。くすんだローズは小さなアクセントだけです。
- 写実、プラスチックCG、グラデーション、質感、重い影、混雑、ランドマークの寄せ集め、反復レイアウトを拒否します。

完全仕様は [SKILL.md](SKILL.md) と [生成プロンプト](references/xxd-panel-050-prompt.en.md) を参照してください。原文の美的動機を守りつつ、歴史的な3:4画布を隠れた既定値にはしません。

## 作例 · 準備中

050 の正式な作例ソースはまだ提供されていないため、他のスタイルの画像を仮置きしません。小小東の検証済み `VOL.050` X 投稿が提供された後、画像を `assets/examples/` に保存し、各画像を原投稿へリンクします。将来の作例も生成参照や既定値にはなりません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1、2、4`、`全部` で一つまたは複数を選択できます。全部では一つの元写真につき7枚の PNG を生成します。

| モード | サイズ未指定時 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 元画像準拠 `W×2H` | 上に元写真、下にデザイン、厳密な50/50 |
| `left-right` | 元画像準拠 `2W×H` | 左に元写真、右にデザイン、厳密な50/50 |
| `design-only` | 元画像準拠 `W×H` | デザインのみ、元写真は非表示 |
| `wallpaper-pack` | 端末別サイズ | スマートフォン、iPad、PC、子ども用時計の個別PNG |

壁紙は連動型または独立型。連動型はすべての端末で元写真と同じ承認済みアンカーを参照し、切り抜きや派生の連鎖を行いません。

## 文案、ラスター、信頼

生成前に自動文案、完全指定文案、文字なしを確認します。言語は対象読者に従い、指定文は一字一句保持します。自動文案は現在の写真の場所、対象、状態、空気、深意、隠れた関係から短い題名とタグラインを作り、都市名公式を使いません。文字は余白と空間リズムへ入り、後付け見出しにはなりません。

通常サイズは元画像に適応し、ペアは厳密に50/50、成果物はすべてPNGです。毎回 `~/Desktop/xxd/xxd-panel-050/` に新しいタスクを作成します。画像生成経路は秘匿情報を表示せず、SVG、HTML、Canvas、プログラム描画は代替になりません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-050.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-050" ~/.codex/skills/xxd-panel-050
```

Claude Code では同じフォルダを `~/.claude/skills/xxd-panel-050` にリンクできます。インストール後にセッションを再起動してください。

完全仕様：[Skill](SKILL.md) · [原始資料](references/050-source.md) · [英語プロンプト](references/xxd-panel-050-prompt.en.md) · [中国語プロンプト](references/xxd-panel-050-prompt.zh-CN.md)

## XXD とサポート

XXD は小小東のブランド名の略称です。作者：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。個別相談は299元／時間、Skills ユーザー交流グループは一回払い99元です。Knowledge Planet＋会員プロンプトライブラリは年額699元の一回の支払いで両方を利用できます。[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) から加入した場合は WeChat で小小東に連絡して[プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)の引換コードを受け取り、プロンプトライブラリで自動開通した場合は WeChat で連絡して Knowledge Planet への招待を受けてください。[WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>地名を替えるのではなく、この写真だけの旅のアイデンティティをつくる。</strong></div>

---

<div align="center">

## ☕ オープンソースを支援

支援は任意で、プロジェクトへのアクセス条件を変えません。

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
