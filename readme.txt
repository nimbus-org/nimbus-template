mvn test コマンドでサンプルを実行する際に-Dservice.target=でサービス定義ファイルまでのパスを記載する。

例）
mvn test -Dservice.target=service/log

上記のコマンドの場合↓↓↓↓が実行される

java classpath ～～～ jp.ossc.nimbus.service.interpreter.BeanShellInterpreterService -servicepath template/${service.target}/service-definition.xml;sample/${service.target}/service-definition.xml -file ${basedir}/target/classes/sample/${service.target}/main.txt
