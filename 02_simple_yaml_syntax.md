--- # YAMLフロントマター使用, markdown以上に構造を明示
task: app_introduction # タスク: アプリ紹介
app_name: MemoBridge # アプリ名: MemoBridge
reference_source: |
  株式会社Aは2025年10月、オンラインノートアプリ「MemoBridge」を正式リリースした。
  このアプリは自動整理・タグ検索・クラウド共有に対応し、
  主に学生やビジネスユーザーを対象としている。
purpose: 製品リリース情報を、誇張や未来予測を避けて伝える # 目的
rules: # ルール
  - 原文以外の情報を加えない
  - 感情的・誇張的な表現を使わない
  - 事実の列挙→概要まとめ の構成
control: # コントロール
  tone: neutral # tone: ニュートラル
  deny_hallucination: true # 幻覚を否定: true
  deny_narrative: true # 物語を否定する: true
output_format: # 出力形式
  - bullets_max: 3 # まとめ行: 3
  - summary_line: true # summary_line: true
---

```markdown
---

# MemoBridge アプリ紹介
## 事実の列挙
* 株式会社Aは2025年10月にオンラインノートアプリ「MemoBridge」を正式にリリースした。
* このアプリは、自動整理・タグ検索・クラウド共有の機能を備えている。
* 主な対象ユーザーは学生およびビジネスユーザーである。
## 概要まとめ
「MemoBridge」は、情報整理と共有を効率化するオンラインノートアプリであり、学習や業務の記録管理を支援する。
```
