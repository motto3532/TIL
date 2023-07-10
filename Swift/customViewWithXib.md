1. xibファイルと`UIView`を継承したswiftファイルを作成
2. swiftファイルにカスタムビュークラスを作成
3. xibファイルの`File's Owner`に先ほど作成したカスタムビュークラスを指定
4. xibファイル上のUIオブジェクトをコードと紐付ける時は、`File's Owner`と紐付ける

### storyboard
5. カスタムビューを表示したいstoryboard上で、対象のviewの`Custom Class`に作成したカスタムビュークラスを指定
6. 何かしらの処理を行いたい場合は、作成したカスタムビュークラス型でviewControllerに紐付け

### コード
5. カスタムビューを表示したいviewをUIView型でviewCOntrollerと紐付け
6. 2で作成したカスタムビュークラスをインスタンス化
  ```例: Customview(frame: customView.bounds)```
7. 6のインスタンスを5のviewに`addSubView()`したらOK
