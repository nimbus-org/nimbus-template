mvn test �R�}���h�ŃT���v�������s����ۂ�-Dservice.target=�ŃT�[�r�X��`�t�@�C���܂ł̃p�X���L�ڂ���B

��j
mvn test -Dservice.target=service/log

��L�̃R�}���h�̏ꍇ�������������s�����

java classpath �`�`�` jp.ossc.nimbus.service.interpreter.BeanShellInterpreterService -servicepath template/${service.target}/service-definition.xml;sample/${service.target}/service-definition.xml -file ${basedir}/target/classes/sample/${service.target}/main.txt
