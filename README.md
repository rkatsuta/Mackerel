# Mackerelのsample
## setup
* mypage
  - https://mackerel.io/orgs/rkatsuta-private/instruction
* installation
  - Debian8以降のagent installを実行
    - https://mackerel.io/orgs/rkatsuta-private/instruction-agent
    - 入んなかった・・・
  - 以下のURLを参考にインストール
    - https://qiita.com/ww24/items/5409aefd87f14beff504
* sensorのメトリクスを送るやつを追加している。
  - https://takanamito.hateblo.jp/entry/2017/02/14/090000
  ```
  [plugin.metrics.sensor]
  command="/home/rkatsuta/sensor/sensor_to_mackerel.sh"
  type="metric"
  ```
