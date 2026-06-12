# 🧠 Paper Review — 知覚・意識・VR 研究解析集

> **Perception · Altered States · Psychedelic VR · BCI**  
> 変性意識・サイケデリックVR・脳-コンピュータインターフェースを軸とした学術論文の深度解析集。  
> 日本語・中文（繁体字）の両言語版を収録。

---

## 📂 収録論文一覧

### テーマクラスター：幻覚・知覚・没入型体験

| # | 論文 | 著者 | 発表 | 解析HTML |
|---|------|------|------|---------|
| 1 | **Hallucination Machine** — Deep DreamとVRで幻覚を安全に再現 | Suzuki et al. | ALIFE 2018 | [🇯🇵 日本語](3DAItoVRXR/hallucination_machine_analysis.html) · [🇨🇳 中文](3DAItoVRXR/hallucination_machine_analysis_zh.html) |
| 2 | **Dreamachine VR** — α波ゲーティングで伪幻覚を誘発するEEG-VRシステム | 亀田ら | IPSJ Interaction 2026 | [🇯🇵 日本語](3DAItoVRXR/dreamachine_vr_analysis.html) · [🇨🇳 中文](3DAItoVRXR/dreamachine_vr_analysis_zh.html) |
| 3 | **Down the Rabbit Hole** — AIWSをVRで体験する心理教育ツール | Verheydt et al. | ACM SIGGRAPH 2023 | [🇯🇵 日本語](3DAItoVRXR/down_the_rabbit_hole_analysis.html) · [🇨🇳 中文](3DAItoVRXR/down_the_rabbit_hole_analysis_zh.html) |
| 4 | **Psychedelics: A Window into Perceptual Processing** — PP理論を否定しGist理論でサイケデリクスを説明 | Brogaard & Gatzia | OUP 2024 | [🇯🇵 日本語](3DAItoVRXR/psychedelics_perceptual_processing_analysis.html) · [🇨🇳 中文](3DAItoVRXR/psychedelics_perceptual_processing_analysis_zh.html) |
| 5 | **Bridging Psychedelic VR and BCI** — EEGクローズドループでDMN抑制、治療的ASC誘発 | Lange, Yenney, Wu | ACM TEI 2025 | [🇯🇵 日本語](3DAItoVRXR/bridging_psychedelic_vr_bci_analysis.html) · [🇨🇳 中文](3DAItoVRXR/bridging_psychedelic_vr_bci_analysis_zh.html) |
| 6 | **Klüver Form-constants** — ブレイクの芸術に幻覚の幾何学を発見する | Worrall | Palgrave Macmillan 2024 | [🇯🇵 日本語](3DAItoVRXR/kluver_form_constants_analysis.html) · [🇨🇳 中文](3DAItoVRXR/kluver_form_constants_analysis_zh.html) |
| 7 | **DreamLLM-3D** — LLMと3D生成AIで夢を没入型体験として再体験 | Liu, Lee et al. | NeurIPS Creative AI 2024 | [🇯🇵 日本語](3DAItoVRXR/dreamllm3d_analysis.html) |

---

## 🗺️ 研究クラスターマップ

```
                    ┌─────────────────────────────────────┐
                    │   知覚の神経科学的基盤                 │
                    │   Klüver Form-constants             │
                    │   Brogaard & Gatzia (Gist Theory)   │
                    └──────────────┬──────────────────────┘
                                   │ V1 → 幻覚パターン
              ┌────────────────────┼───────────────────┐
              ▼                    ▼                   ▼
   ┌─────────────────┐  ┌──────────────────┐  ┌────────────────────┐
   │  VRによる        │  │  BCI × VR        │  │  夢の可視化         │
   │  幻覚再現        │  │  神経フィードバック │  │  DreamLLM-3D       │
   │                 │  │                  │  │                    │
   │ Hallucination   │  │ Dreamachine VR   │  │ LLM + Point-E      │
   │ Machine         │  │ (α波ゲーティング)  │  │ → Unity3D          │
   │ Down the        │  │ Bridging VR&BCI  │  └────────────────────┘
   │ Rabbit Hole     │  │ (DMN抑制)         │
   └─────────────────┘  └──────────────────┘
```

---

## 📖 解析の読み方

各HTMLファイルをブラウザで開くと、以下を含む深度解析が読めます：

- **Mermaid フロー図** — システムアーキテクチャ・メカニズムの可視化
- **核心摘要ボックス** — 5行で論文の要点を把握
- **論文原文引用** — 著者の言葉をそのまま
- **関連研究との比較表** — クラスター内の論文を横断的に理解
- **限界と課題** — 著者自述 + 独立評価

---

## 🧵 共通テーマ

このリポジトリの論文群は、**一つの問い** を複数の角度から探求しています：

> **「ヒトの知覚はどこまで操作・拡張・再現できるか？」**

- 神経科学：V1の自発パターン → 幻覚の幾何学（Klüver、Brogaard）
- VR技術：幻覚の外在化・再現（Hallucination Machine、Down the Rabbit Hole）
- BCI統合：脳波で閉じたループ、意識状態の誘導（Dreamachine VR、Bridging VR&BCI）
- 夢研究：無意識体験の可視化と再体験（DreamLLM-3D）

---

## 🛠️ 技術スタック（解析ファイル）

解析HTMLは以下で構築：

- **[Mermaid.js](https://mermaid.js.org/)** — フロー図・アーキテクチャ図
- **[KaTeX](https://katex.org/)** — 数式レンダリング（学術型解析）
- カスタムCSS — 論文ごとにテーマカラーを設定

---

## 📌 今後追加予定

- [ ] GitHub Pages での公開（HTMLをブラウザから直接閲覧可能に）
- [ ] 解析間のクロスリファレンスリンク追加
- [ ] DreamLLM-3D 中文版

---

*解析生成: `/paper-analyzer` スキル（Claude Code）*
