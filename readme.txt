各サブプロジェクトでのサンプル実行方法

> mvn test

template/service-definition.xml と sample/service-definition.xml を読み込み sample/main.txt を実行する


> mvn test -Dsample.target=hoge

template/service-definition.xml と hoge/service-definition.xml を読み込み hoge/main.txt を実行する


> mvn test -Dsample.target=hoge/fuga

template/service-definition.xml と hoge/fuga/service-definition.xml を読み込み hoge/fuga/main.txt を実行する

