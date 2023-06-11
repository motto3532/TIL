# `storyboard reference`でstoryboardを分ける
1. 新しく`viewController`と`storyboard`を追加
2. `viewController`と`storyboard`を紐付け
3. `storyboardID`を設定
4. `viewController`の`is initial view controller`にチェック
5. 親の`storyboard`に`containerView`と`storyboard reference`を追加
6. `containerView`から`storyboard reference`に`segue`を`embed`で設定
7. `storyboard reference`に3で設定した`storyboardID`を設定

> `storyboard`上で`viewController`の形を変えたい時は、`simulated size`を`freedom`にする
