git config --global user.name "mc"
git config --global user.email "your_email@example.com" 
�û������ʼ���Ϊȫ��Ψһ��ʶ
git init ��Ŀ¼���git����ֿ�
cd ����
mkdir ����Ŀ¼
pwd ��ʾ��ǰĿ¼·��
rd ɾ���ļ� 
git add "xxx.txt" ���ļ����뵽������
git commit -m "��ע" ȷ��ǩ��
git diff readme.txt �鿴����
git status �鿴״̬
git log �鿴ǩ����־
git log --pretty=oneline �鿴��д��־
git reset --hard head^ �ع���һ��
git reset --hard head^^ �ع�������
git reset --hard head~100 �ع���100��
git relog �鿴�汾��
git reset --hard 6fcfc89 �ع����ض��汾��
git checkout -- readme.txt �������������޸�
cat readme.txt �鿴�ļ�����
touch README.md �����ļ�


ls -al ~/.ssh �鿴����ssh key
ssh-keygen -t rsa -b 4096 -C "your_email@example.com" ����SSH
eval "$(ssh-agent -s)" ����ssh Agent
ssh-add ~/.ssh/id_rsa �ӵ�ssh Agent
git remote add origin https://github.com/xxx/xxx.git
git push -u origin master
git clone https://github.com/rickxie/mctest.gt ��¡Զ�̿�
git checkout -b dev ����dev��֧ git branch dev/ git checkout dev
git branch �鿴��ǰ�ķ�֧
git merge dev ��dev merge����ǰ��֧
  
�鿴��֧��git branch

������֧��git branch name

�л���֧��git checkout name

����+�л���֧��git checkout �Cb name

�ϲ�ĳ��֧����ǰ��֧��git merge name

����ǰ������������ git stash
�鿴�����ֳ�  git stash list
�ָ������ֳ� git stash apply
ɾ�������ֳ� git stash pop

�鿴Զ�̿���Ϣ git remote
��ϸ��Ϣ git remote -v

��Զ��origin dev��֧�������� git checkout  �Cb dev origin/dev
������dev��֧���͵�Զ��ȥ git push origin dev
��ȥ���� git pull
���ñ��ط�֧��Զ�̵����� git branch --set-upstream dev origin/dev

ɾ����֧��git branch �Cd name
ɾ��Զ�̹���:  git remote rm origin
��ס�˺�����: git config --global credential.helper store
