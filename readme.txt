���زֿ⣺
 1.��װgit 

    ����Ƿ�װgit��git --version

    debianϵ�а�װ���sudo apt-get install git 

    windowsϵ�У�һ����װmsysgit

2.�����û�

    git config --global user.name "name"

    git config --global user.email "email@xx.xxx"

3.��������ʼ��һ���ղֿ�

    mkdir warehouse_name   //�½��ļ�����Ϊ�ֿ�

    cd warehouse_name      //�����ļ���

    git init               //��ʼ��Ϊ�ֿ⣬�Զ�����.git

4.�ύ�ļ����ֿ�

    git add file1 file2 ...  //���ļ����뻺����

    git commit -m "��ʾ��Ϣ"  //�����������ļ�ȫ���ύ���ֿ⣬-m�����ʾ��

Ϣ

    git status               //�鿴������״̬

    git diff                 //�鿴���ĵ�����

5.�汾����

    git log �� git log --pretty=oneline  //�鿴��ʷ�汾

    git reset --hard HEAD^       //����ڵ�ǰ�汾�Ļ��ˣ�����HEAD��ʾ��ǰ>�汾,HEAD^��ʾ��һ�汾��HEAD^^��ʾ���ϰ汾���Դ�����

    git reset --hard commit_id    //ָ��commit_id�İ汾���ˣ�commit_idΪ�ļ�hashֵ����ֻд��λ

    git reflog                   //��ʾ��ʷ��������

6.С��

    �ճ�ʼ������.git�ļ���ʵ���ǰ汾��

    add���ǰѹ��������ļ���ӵ��汾���еĻ�������stage����commit���ǽ�����

����stage���е��ļ��Ž�master���в���ջ�������stage�� 

7.����������ɾ������

    git checkout -- filename    //�����������ļ����������������ļ�����û

�У���ص���ǰ�汾��HEAD��ͬ״̬�����Ѿ��ύ�汾�⣬��ο��汾����

    git reset HEAD filename     //�ѻ��������޸ĳ����������·Żع�����

    git rm & git commit         //ɾ���汾������ļ�������