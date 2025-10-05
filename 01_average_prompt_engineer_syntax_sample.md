```markdown
# 平均的プロンプトエンジニア構文（比較用）

## 解説
- * **平均的プロンプトエンジニア構文** は、平均的なプロンプトエンジニアが実務で使う単純な要約指示です。
- * markdown形式を使用しています。
- * 文頭にタスク説明と出力形式指定のみを簡潔に書くだけで、レイヤー制御や複雑な安全対策は含みません。
- * 層制御や安全レイヤーの記述はなく、「シンプルな指示」「短い出力」「要約禁止事項」程度に留めています。
- * これは平均年収が507〜900万円程度の「普通のプロンプトエンジニア」レベルを想定したものです。
```
```markdown
# シンプル要約プロンプト
以下の文章を読み、重要なポイントを3〜5個の箇条書きでまとめてください。文章の内容を忠実に反映し、主観や推測は入れないでください:contentReference[oaicite:14]{index=14}。

文章:
"""
株式会社Yは2025年10月1日にAI分析ツール「InsightPro」を発表した。
同ツールは企業のデータ分析を自動化し、レポート作成時間を大幅に短縮する。
初期リリースは日本国内向けで、今後海外展開も検討中。
料金プランは月額制で、中小企業でも導入しやすい価格設定。
開発チームは今後、ユーザーのフィードバックをもとに機能強化を進める予定。
"""

出力形式:
- 箇条書き（「・」または「-」）を使い、各項目は20字以内を目安に短くまとめます:contentReference[oaicite:15]{index=15}。
- 箇条書きの後に1行で簡潔なまとめを書くと読み手に親切です。
```

```markdown
出力例:
* 2025年10月1日に「InsightPro」発表
* データ分析を自動化
* レポート作成を短縮
* 日本向け初期リリース
* 海外展開を検討中

**まとめ:**
株式会社Yが発表したAIツール「InsightPro」は、企業のデータ分析とレポート作成を効率化し、今後は機能強化と海外展開を予定している。
```


<img width="1207" height="846" alt="average_prompt_engineer_syntax_sample_image" src="https://github.com/user-attachments/assets/c41e96e8-2256-430c-90c4-dcca889973d9" />



```text
↑本文は画像の箇所まで。
↓ここから下はただのjson形式でのsignatureとhashなので、メタデータ記録用。本文とは一切関係ありません。
コード保護のため、nazuna-2371独自で追加した物です。
```

```json
{
  "meta_data": {
    "usage": "平均的プロンプトエンジニア構文（比較用）",
    "notes": [
      "解説", "構文本体", "出力例", "動作例画像"
    ],
    "revision_notes": {
      "previous_version": "1.0.0",
      "diff_detail": "最新verなので差分無し。"
    },
    "file_name": "init_various_feature_control_syntax_20250929.json",
    "version": "1.0.0",
    "author": "nazuna-2371",
    "created": "2025-10-05",
    "last_updated": "2025-10-05"
  }
}
```

```json
{
  "whole_signature_and_integrity_checksum": {
    "signature": "nazuna-2371",
    "hashing_range": {
      "target_1": "先頭からmeta_dataまで",
      "hash_value": {
        "sha512": "33ff28b3a57b90537de4dab0898a5429b4afa42fe6dc1c1a0fde4638138031d78e68d6516177e4d5813401c52eceaa362df4eb61c365be9298bf5d4391e9d74e",
        "sha256": "82bb8f745190568c8fc6a5ee17b87cb0efd063bcb04b6f11cb45f4c63d709602",
        "md5": "d6c4887db838604c60f4812874909728"
      },
      "target_2": "png画像エリアのみ",
      "hash_value": {
        "sha512": "03b19fc17744513b1dd8e3d9cf38e6dbd1f34ba1c1ca535c0bf1f59058850253d5a05e8fe18dc05ba13447d55b331962b342b63612d068d3389c91ea4e6b506b",
        "sha256": "10ce70fb8df6b6ee0fe94802ff29188484ea53949d7cea74de81d79506d89b48",
        "md5": "909f16a38a7da557b085f3f32a7b1ef3"
      }
    }
  }
}
```
