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

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091461184516227185) · 2026年8月23日<br>
> GPT2 × ベクターイラスト × 旅 × ミニマル × 美学プロンプト × VOL.050

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 050 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 050 作例 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 050 作例 3"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 050 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元画像ごとに7点の独立PNGを出力します。モード選択後、生成前に完成画像全体の画角を必ず確認します：元プロンプトの `3:4`、明示的な元画像比率、一般的な比率、またはカスタム比率／正確なピクセルです。元画像寸法を暗黙には適用しません。

| モード | 画角ルール | 成果物 |
| --- | --- | --- |
| `top-bottom` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：上に高忠実度の元画像、下に 050 デザイン、約50/50 |
| `left-right` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：左に高忠実度の元画像、右に 050 デザイン、約50/50 |
| `design-only` | ユーザー確認済みの完成画角 | 050 デザインが全画面を満たし、元画像は表示しない |
| `wallpaper-pack` | 端末ごとに確認 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

二連モードは元画像を高忠実度の編集／参照入力として使い、完全なスタイルプロンプト一式で完成画面を直接生成します。写真、デザイン、色、光、文字、意味を一体化するためです。決定論的な合成は、完成画面の再試行後も失敗した場合、原画像のピクセル完全保持を明示された場合、生成経路が指定画角に対応しない場合、または無劣化の最終ピクセル調整が必要な場合だけ使います。

壁紙は連動または独立を選べます。連動はiPad基準作を一つ承認し、他の端末を元画像＋同じ基準作から個別に再構成します。独立は各端末が元画像だけを参照します。どちらも他端末の成果を切り抜かず、派生を連鎖しません。

## 文案、ラスター、信頼

生成前に自動文案、完全指定文案、文字なしを確認します。言語は対象読者に従い、指定文は一字一句保持します。自動文案は現在の写真の場所、対象、状態、空気、深意、隠れた関係から短い題名とタグラインを作り、都市名公式を使いません。文字は余白と空間リズムへ入り、後付け見出しにはなりません。

通常サイズは元画像に適応し、ペアは厳密に50/50、成果物はすべてPNGです。毎回 `~/Desktop/xxd/xxd-panel-050/` に新しいタスクを作成します。画像生成経路は秘匿情報を表示せず、SVG、HTML、Canvas、プログラム描画は代替になりません。

## 画像モデルの優先順位

GPT Image 2 を既定の第一候補とします。高忠実度の参照画像、生成前の完成キャンバス確認、二連モードの完成画面一括生成、条件を満たした場合だけのスクリプト合成という既存の流れは変わりません。

現在のツールまたは設定済み経路から実際に利用でき、元画像の忠実度、完成画角、対象言語の文字、連動壁紙の複数参照を満たせる場合は、Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）、その他の互換ビットマップモデルも利用できます。代替モデルが変更できるのは生成経路だけで、モード、画角、文案、言語、壁紙関係、完成キャンバス優先の方針は変更できません。

適切な経路がない場合は、画像生成ツールを有効にするか API Key を提供するようユーザーに案内します。ユーザーが提供した認証情報は現在のタスクで利用できますが、返信やログに再表示・記録・開示しません。明示的な依頼がない限り、長期保存やプロバイダー、アカウント、課金、グローバル経路の設定変更も行いません。

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
