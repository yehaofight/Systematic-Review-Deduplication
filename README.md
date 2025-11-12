# Systematic-Review-Deduplication
EndNote 無法智能去除『模糊重複』的文獻。
使用 Python Pandas 讀取資料，並利用 Fuzzywuzzy 演算法，設定 95% 及 85-94%  的門檻，進行雙重比對。
從 2732 筆 原始資料中，成功辨識並移除了 177 筆 垃圾資料和 791 筆 模糊重複的文獻，最終得到 1764 筆  黃金標準資料庫。
