# voice-test（音声ツール2本）

## ピッチ判定ツール（pitch.html）
公開URL: https://misokichi13.github.io/voice-test/pitch.html

歌や発声の音程を確認するツールです。基準音を鳴らして、自分の声のピッチ（音名とセント差）をリアルタイムで表示します。

- マイクの増幅と感度はスライダーで調整できます
- 声をまっすぐ保つ練習（伸ばした音の震えの確認）にも使えます

## 音声モニタリング（index.html）
公開URL: https://misokichi13.github.io/voice-test/

配信中の発話を音声認識で取り込み、1分ごとにGeminiが「良好／やや疲労／要休憩」の判定とアドバイスを表示します。

- Gemini APIキーが必要です（画面から保存。ブラウザ内にのみ保存されます）
- 音声認識はブラウザ依存の機能です。iPhoneではSafariでの利用が前提です
