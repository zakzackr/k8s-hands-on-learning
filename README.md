# k8s-hands-on-learning

## Keyword

**マニフェスト**  
Kubernetes リソース（Pod、Deployment、Service など）の設定を定義した YAML/JSON ファイル。

**Pod**  
Pod は kubernetes における最小のデプロイ単位で、ストレージやネットワークを共有する、1 つ以上のコンテナ群。  
コンテナには単一のアプリケーションだけを含めることが一般的だが、Pod を使用することでそれらを保ちながら関連のあるアプリケーションをまとめて扱うことができる。

**Deployment**  
稼働する Pod 群を管理する。Pod のスケーリング、アップデート、自動復旧などを担当する。
