# RESTと比較した時のgRPCの長所
- HTTP/2による高速な通信
- Protocol Buffers
- 柔軟なストリーミング形式
  

## Protocol Buffers
- IDL（インターフェース記述言語）
- スキーマファースト
  - 静的型付けを行う

# ４つのPRC形式
- シンプルなRPC
- サーバーストリーミングRPC
- クライアントストリーミングRPC
- 双方向ストリーミングRPC

# RESTと比較した時の短所
- HTTP/2非対応である危険性
  - AWS ALBが2020年10月にHTTP/2に対応したことで参入障壁はだいぶ下がった
- ブラウザの対応が不十分
  - 実際はどうなのか？
- 言語によって機能の実装状況にばらつきがある
  - PHPやRubyは遅れがち
- バイナリにシリアライズすると人間が読めない
- RESTも十分早い

## スキーマファースト開発による生産性の高さが最大の長所
- だったらGrapQLでも良い気がするし、RESTも拡張すれば対応可能

### gRPCのgは何か？
バージョンによって異なる。Googleのgでは無い