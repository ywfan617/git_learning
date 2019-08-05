# anaconda学习  

## anaconda常用命令  

```bash
    conda create [env] python=3 #创建环境
    # conda create -n learn python=3
    conda env list #列出环境
    activate #activate 能将我们引入anaconda设定的虚拟环境中, 如果你后面什么参数都不加那么会进入anaconda自带的base环境
    source activate learn #切换环境
    conda env export > environment.yaml #导入导出环境
    conda env create -f environment.yaml #当需要重新创建一个相同的虚拟环境时可以用
    conda env remove -n env_name #删除环境
```

```bash
    conda --version #检查版本号
    conda upgrade --all #更新软件包
    conda install requests #安装第三方库
    conda remove requests #卸载大三方库
    conda list #查看当前包的信息
    conda info #展示当前conda的一些信息
    conda search package #查询包
```

## 删除anaconda  

```bash
    rm -rf anaconda #把 ~/.bashrc的环境变量清除掉
```  
