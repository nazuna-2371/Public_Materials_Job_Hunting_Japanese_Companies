```json
{
  "task": "app_introduction",
  "app_name": "MemoBridge",
  "description": "JSON（機械制御 / 定量パラメータ入り"
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
```markdonw
以下は、指定の条件に基づいて作成した「MemoBridge」アプリの紹介文です。
---
### MemoBridge アプリ概要
* 株式会社Aは2025年10月にオンラインノートアプリ「MemoBridge」を正式にリリースした。
* アプリは自動整理機能、タグ検索機能、クラウド共有機能を備える。
* 主な対象ユーザーは学生およびビジネスユーザーである。
**まとめ:**
MemoBridgeは、情報整理と共有を効率化するためのオンラインノートアプリである。
```
