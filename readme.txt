һ������һ��������Google App Engine(GAE)�ϵ�Kindle�������ͷ������������Ű澫������־ģʽMOBI��ʽ�Զ�ÿ������������kindle��
    ����վӦ��Ŀǰ�Ĺ����У�
    1.֧������calibre��recipe��ʽ���Զ���RSS�ռ�����Ҫд���룬��Ҫ��һ���python����
    2.�Զ���RSS������Ҫpython������ֱ������RSS���Ӻͱ��⼴���Զ�����
    3.���˺Ź���Ҳ����֧�ֶ�kindle
    4.��ͼ����־��ʽMOBI
    5.�Զ�ÿ�춨ʱ����

    ע�������Ҫ�󲻸ߣ��Զ���RSS���͹�����Ӧ��һ��Ӧ�ã����Ҫ���Ű�����������Բ���booksĿ¼�µ��ļ��Լ�����һ���ļ���
    ������python��ǰ���£���������ȫ�Ĳٿ���ҳ��������������Ҫ����������MOBI�ļ���

���������裺
    1.����GAE�˺Ų�����һ��application��https://appengine.google.com/
    2.����GAE SDK��https://developers.google.com/appengine/downloads?hl=zh-CN
    3.��װPython 2.7 ����Ѿ���װ�ˣ������˲���
    4.���ر�Ӧ�õ������ļ����ŵ�һ���ض���Ŀ¼��
    5.�޸�app.yaml�ĵ�һ�У���kindleear�޸�Ϊ�������application����
    6.�޸�main.py�е��⼸������
      SrcEmail ��������GAE�˺�ʱ��GMAIL����
      TIMEZONE ��Ĭ��ʱ��
      OWNFEEDS_TITLE ���Զ���RSS���͵�kindle����ʾ���鼮����
    7.ת��GAE SDK��װĿ¼��Ĭ��Ϊ��C:\Program Files\Google\google_appengine��
      ִ��CMD���c:\python27\python.exe appcfg.py update ���kindleear�����ļ���Ŀ¼
      ���磺c:\python27\python.exe appcfg.py update kindleear
      ����������������룬�Ƚ�����Ϳ��Դ�������
      application��.appspot.com
      ��ʼ���ĸ������ͷ����ˡ�
      ע����ʼ�û�Ϊadmin������Ϊadmin�������½��ʱ�޸����롣
