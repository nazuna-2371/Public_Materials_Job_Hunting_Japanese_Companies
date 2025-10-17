---
task: app_introduction
app_name: MemoBridge
reference_source: |
  株式会社Aは2025年10月、オンラインノートアプリ「MemoBridge」を正式リリースした。
  このアプリは自動整理・タグ検索・クラウド共有に対応し、
  主に学生やビジネスユーザーを対象としている。
purpose: 製品リリース情報を、誇張や未来予測を避けて伝える
rules:
  - 原文以外の情報を加えない
  - 感情的・誇張的な表現を使わない
  - 事実の列挙→概要まとめ の構成
control:
  tone: neutral
  deny_hallucination: true
  deny_narrative: true
output_format:
  - bullets_max: 3
  - summary_line: true
---

```makrdonw
**事実の列挙**
* 株式会社Aは2025年10月にオンラインノートアプリ「MemoBridge」を正式リリース。
* アプリは自動整理機能、タグ検索機能、クラウド共有機能に対応。
* 主な対象ユーザーは学生およびビジネスユーザー。
**概要**
MemoBridgeは、整理・検索・共有を効率化するオンラインノートアプリとして提供されている。
```
