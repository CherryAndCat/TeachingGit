# Gitʹ�ý̳�

ǰ�ý̳�

## [git����GitHub�Ƽ��̳� ](https://www.cnblogs.com/linshengqian/p/15065553.html)

���ʹ�ô������޷����ӵ����,ֱ�ӹرմ�����
> git config --global http.sslVerify false





1������dev��֧

```bash
git checkout -b dev
```

<mark>2�������ص� demo ��֧���б��ص� commit �ύ��</mark>

```bash
git add .
git commit -m "����� dev �Ŀ���"
```

<mark>3�������ص� dev ��֧���͵�Զ�ֿ̲���б��棺</mark>

```bash
git push -u origin dev
```

4�������ص� dev ��֧�ϲ������ص� main ��֧��

```bash
git checkout main
git merge dev
```

5���������3�޷����ͣ������ǳ�ͻ���£�������`git pull`�ȴ�Զ�ֿ̲�ͬ�������أ�ʵ�ڲ��о������Ƚ�һ���µķ�֮����ȥ���������



##  ʹ�õ�ͼ�λ�����

- vscode �� Jetbrains���Ƽ���
- [Fork](https://git-fork.com/)
- [GitHub Desktop](https://desktop.github.com/)
- [![Sourcetree logo](https://wac-cdn.atlassian.com/dam/jcr:f32681c1-355d-4806-b29c-319b0c6ecb06/Sourcetree-blue.svg?cdnVersion=1227)](https://www.sourcetreeapp.com/)

