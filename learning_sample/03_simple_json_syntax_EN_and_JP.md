```json
{
  "task": "app_introduction",
  "app_name": "MemoBridge",
  "description": "Json（機械制御 / 定量パラメータ入り）",
  "reference_source": "株式会社Aは2025年10月、オンラインノートアプリ「MemoBridge」を正式リリースした。\nこのアプリは自動整理・タグ検索・クラウド共有に対応し、\n主に学生やビジネスユーザーを対象としている。",
  "purpose": "製品リリース情報を、誇張や未来予測を避けて伝える",
  "rules": [
    "原文以外の情報を加えない",
    "感情的・誇張的な表現を使わない",
    "事実の列挙→概要まとめ"
  ],
  "control": {
    "tone_control": {
      "formality": 0.8,
      "creativity": 0.2,
      "dramatic_performance": 0.1
    },
    "logic_control": {
      "inference_precision": 1.0,
      "inference_depth": 0.85,
      "contradiction_exclusion": 1.0
    },
    "constraints": {
      "deny_hallucination": true,
      "deny_narrative": true
    }
  },
  "output_format": {
    "bullets_max": 3,
    "summary_line": true
  }
}
```

```markdown
以下は指定条件に基づく「MemoBridge」紹介文（定量・論理整形済）です。

---
### 製品情報（事実列挙）
* **製品名**：MemoBridge
* **提供元**：株式会社A
* **リリース時期**：2025年10月
* **機能**：自動整理、タグ検索、クラウド共有
* **主対象ユーザー**：学生、ビジネスユーザー
---
### 概要（要約）
MemoBridgeは、株式会社Aが2025年10月に正式リリースしたオンラインノートアプリであり、情報整理や共有を効率化する基本機能を備えている。
```
