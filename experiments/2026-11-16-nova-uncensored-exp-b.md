# NOVA Uncensored Exp B（2026-11-16）

- ベースモデル: tokyotech-llm/Qwen3-Swallow-8B-SFT-v0.2
- 目的: 日本語での過剰拒否低減、教育・研究文脈での回答力強化
- データ: 211件（過剰拒否緩和60 / 数学53 / アイデンティティ28 / 化学35 / セキュリティ35）、train 189 / val 22
- 生成: Kaggle上で generate_complete_dataset.py により生成（数学はSymPy併用）。スクリプト実測値（ヘッダー記載の218件とは不一致）
- 生成コード: code/nova-uncensored-exp-b/generate_complete_dataset.py
- ステータス: データセット生成完了
- 公開ページ: nova-uncensored-exp-b.html
