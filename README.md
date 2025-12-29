# k8s-hands-on-learning

## Keyword

**マニフェスト**  
Kubernetes リソース（Pod、Deployment、Service など）の設定を定義した YAML/JSON ファイル。

**Pod**  
Pod は kubernetes における最小のデプロイ単位で、ストレージやネットワークを共有する、1 つ以上のコンテナ群。  
コンテナには単一のアプリケーションだけを含めることが一般的だが、Pod を使用することでそれらを保ちながら関連のあるアプリケーションをまとめて扱うことができる。

**Deployment**  
稼働する Pod 群を管理する。Pod のスケーリング、アップデート、自動復旧などを担当する。Deployment では Pod の削除とともに、データも削除される。

**StatefulSet**
StatefulSet は、ステートフルな Pod 管理に使用される。各 Pod に固有のボリュームを割り当てることで、データの永続化が可能になり、Pod の削除・再起動後も一貫したデータを持つ。各 Pod をインデックスで一意に識別・管理することで、正しい順序（インデックス順）で Pod の起動・終了が可能。

**Headless Service**
