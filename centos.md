## �apache

- ��putty �����¼��ʱ�� ��������û��Ӧ (��������)
- ����xhell ֱ�������û������� ��¼(��Դ�һ�㹦�� ��ȫ) ��ʵ��װApache���� ��װhttpd
- 1 ��װ ָ��  yum install httpd Ȼ��y ���
- 2 �������� ָ�� 
  systemctl start httpd.service
- ֹͣ���� ָ�� systemctl stop httpd.service
- 3 ����Apache���� vi/etc/httpd/conf/httpd.conf
  �޸��������� #Listen 12.34.56.78.80 ģ�¸��� д�����ip��������,���ط���ip��ַΪ127.0.0.1, ����б��� �Ͱ���ϵͳ����ʾ һ��һ�����.
- 4 ���������ֱ����server NAME
- 5 ������ķ�������ַ �����ʾApache�Ĳ���ҳ��˵�������ɹ���
- 6 ϵͳ�����ʾhttpd�Ѿ�����,���Խ�������httpd����,�����¿���.
  killall httpd
  systemctl start httpd.service





