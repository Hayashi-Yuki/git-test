
#Git ��װ�̳̼�Github ����
�˰�װ�̳̲ο� 

* https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git(����) 

* http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137396287703354d8c6c01c904c7d9ff056ae23da865a000  (��ѩ��̳�) 

����ֻ�� Windows �ϰ�װ������ȷ������ϵͳ���尲װ�������ҿɿ���ֱ������������ӽ��а�װ�������˺���������û��������䲿�ֺ����� github �Ĳ���) 


###Linux 
���ȣ�����``git``������ϵͳ��û�а�װ Git�����û�а�װ��һ����������ΰ�װ Git 

���� 
```
$ git 
The program 'git' is currently not installed. You can install it by typing:
sudo apt-get install git 
```
###Mac
�� Mac �ϰ�װ Git �ж��ַ�ʽ�� ��򵥵ķ����ǰ�װ Xcode Command Line 
Tools��Mavericks��10.9������߰汾��ϵͳ�У���``Terminal``�ﳢ���״�����``git``����ɡ����û�а�װ�������п����߹��ߣ�������ʾ�㰲װ�� 
������밲װ���µİ汾,����ʹ�ö����ư�װ����.�ٷ�ά����OSX Git��װ��������� Git �ٷ���վ���أ���ַhttp://git-scm.com/download/mac 
###Windows (MinGW)

�� https://git-for-windows.github.io ���� msysgit��Ȼ��Ĭ��ѡ�װ���ɡ� 
��װ��ɺ��ڿ�ʼ�˵����ҵ���Git��->��Git Bash�����ĳ�һ�����������д��ڵĶ�������˵�� Git ��װ�ɹ���

![git bash](http://wuch15.github.io/git1.jpg)

��װ��ɺ󣬻���Ҫ���һ�����ã������������룺
```
$ git config --global user.name "Your Name" 
$ git config --global user.email "email@example.com"
```
ͨ��������ָ�����زֿ��Ӧ���ü����� Email ��ַ�� 
ע�� git config �����--global ���������������������ʾ����̨���������е� Git �ֿⶼ��ʹ��������ã���ȻҲ���Զ�ĳ���ֿ�ָ����ͬ���û����� Email ��ַ�� 


##Github���� 

���ȣ���Ҫ��һ�� github �˺� https://github.com/

������������� Git ������� SSH Key ��Կ��: 

    ssh-keygen �Ct rsa �CC ��emailaddress�� 
    
��ʱ�����û���Ŀ¼�µ�.ssh Ŀ¼�п��� id_rsa(˽Կ) �� id_rsa.pub(��Կ) 

��½ Github���� Account Setting������ SSH Key ���棬�� Add SSH Key����������title ���� Key �ı�����ճ�� id_rsa.pub �е����ݲ���Add Key 

![github](http://wuch15.github.io/git2.jpg)
