## Toast Global UI のモジュール単位の責務

### Toast コンポーネント

- View を提供する

### ToastProvider コンポーネント

- 表示のための状態を保持する

### useToastProvider フック

- 表示ロジックを管理する
- 案件とかではコンテキスト定義するとこに一緒に書いてた

### useToastAction フック

- 子孫コンポーネントから呼び出す
