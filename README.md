# plotly_test

- 日付を一旦、indexにして月ごとに集計
- reset_indexで再び日付を列に戻す。
- df.melt(id_vars='date')でdate列以外の列（株式の種別）をvariable列に集約する。
- 描画時にxaxis=dict(tickformat='%Y年%m月',dtick='M1')　で1ヵ月毎に日本語日付で表示


![image](https://user-images.githubusercontent.com/38909218/205910417-85ca01ca-1470-424f-a400-5d03de87b244.png)
