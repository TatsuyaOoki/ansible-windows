# set_hostname

## 処理内容

1. ホスト名の設定\
  **以降の処理はホスト名がタスクによって変更された場合にのみ実施**

2. OS再起動
3. ホスト名の取得
4. ホスト名変更前と変更後の比較

## 変数の設定

| 変数名 | 説明 | 備考 |
| ----- | ----- | ----- |
| set_hostname_name | 対象ホストに設定する新しいホスト名 | |

## 注意事項

> [!IMPORTANT]
> ホスト名はデフォルトでインベントリ名の値が設定されます
