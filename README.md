word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  
word  

# make


## ��Զ�ֿ̲��ȡ

* ��Զ�˲ֿ�fetch������ͬʱmerge

```
$ git pull origin master    
```

* ������fetch + merge  
* origin/master����Զ�ˣ�github������Ĳֿ⣬master���Ǳ��صĲֿ�  

```
$ git fetch orgin  
$ git merge master origin/master  
```

## git merge��ͻ
�Զ��ϲ�ʧ�ܣ���Ҫ�ֶ������ͻ

* ��ͻ�鿴
```
$ git diff
```

* �����ͻ���༭��ͻ�ļ����ѳ�ͻ�Ĳ���ɾ�������޸ĵ�
![conflict file](./images/git/merge.png)

��ͼ�б�����ǵĲ��֣�ǰ�������֮��Ĳ��֣��Ǳ��ص����ݡ�  
���������֮��Ĳ��֣���origin/masterԶ�˵����ݡ���ô�޸ľ������㡣�������Ҫ�Ѻ�������ɾ��  


## ���͵�Զ�ֿ̲�
* push file to the master of remote reposity

```
$ git add lecture-3
$ git commit -m ��bbbbb"
$ git push origin master
```

* ������test��֧����Ϊupstream�����͵�Զ�ֿ̲�

```
git push --set-upstream origin test  
```
