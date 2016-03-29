SteveYangHJ.github.io
=====================
  Create new blog for Steve

  
中标题
-----------------------------------
  中标题一般显示重点项,类似html的\<h2\><br />
  你只要在标题下面输入------即可
  
### 小标题
  小标题类似html的\<h3\><br />
  小标题的格式如下 ### 小标题<br />
  注意#和标题字符中间要有空格

### 注意!!!下面所有语法的提示我都先用小标题提醒了!!! 

### 单行文本框
    这是一个单行的文本框,只要两个Tab再输入文字即可
        
### 多行文本框  
    这是一个有多行的文本框
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可
    这里你可以输入一段代码

### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧
    public class HelloWorld {

        /**
         * @param args
         */  
       public static void main(String[] args) {
            System.out.println("HelloWorld!");

        }
     }
    
### 链接
1.[点击这里你可以链接到www.google.com](http://www.google.com)<br />
2.[点击这里我你可以链接到我的博客]()<br />

###只是显示图片
![github](http://github.com/unicorn.png "github")

###想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com
[![image]](http://www.github.com/)
[image]: http://github.com/github.png "github"

### 文字被些字符包围
> 文字被些字符包围
>
> 只要再文字前面加上>空格即可
>
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
> 但> 只能放在行首才有效

### 文字被些字符包围,多重包围
> 文字被些字符包围开始
>
> > 只要再文字前面加上>空格即可
>
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
>
> > > > 但> 只能放在行首才有效

### 特殊字符处理
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>

### 显示表格问题
| 特性 | Maven中央仓库 | EBR |
| ---- | ---- | ---: |
| OSGi 兼容性| 不明确 | Yes |
| 工件数量 | 成千上万，所有类型 | 几百个，只有那些Spring集成的 |
| 一致的命名约定| No | Yes |
| 命名约定：GroupId | 多种多样。新的工件使用域名，比如org.slf4j。旧的经常仅仅使用工件名称，如：log4j | 原始域名或主要包的根路径，如：org.springframework |
| 命名约定：ArtifactId | 多种多样。通常通常是项目或模块名称，使用连字符“-”分隔符，如：spring-core | Bundle符号名，从主包根路径派生，如：org.springframework.beans。如果jar必须被修补来确保OSGi兼容性，则会附加com.springsource，如：com.springsource.org.apache.log4j |
| 命名约定：Version版本| 多种多样。许多新的工件使用m.m.m或者m.m.m.X(其中m=数字，X=文本)。旧的使用m.m。一些不是这两种情况的任何一种。定义了排序但是并不经常被依赖，所以不是严格可靠的 | OSGi版本号m.m.m.X，如：3.0.0.RC3。文本限定符对相同数值的版本进行排序 |
| 发布| 通常通过远程同步（rsync）或者源代码控制更新。项目作者可以单独上传jars到JIRA。 | 手工的（由SpringSource处理JIRA） |
| 质量保证| 依据规则。准确来讲，是作者的责任。 | 广泛的OSGi清单，Maven POM和Ivy元数据。Spring团队会解答QA |
| 托管| Contegix. 由Sonatype资助了多个镜像 | SpringSource资助的S3 |
| 搜索工具| 多种多样 | http://www.springsource.com/repository |
| 与SpringSource工具的集成| 通过STS和Maven依赖管理集成| 通过STS广泛的集成Maven、Roo、CloudFoundry |

| 特性 | Maven中央仓库 | EBR |
| ---- | ----  | --- |
| OSGi 兼容性| 不明确 | Yes |
| 工件数量 | 成千上万，所有类型 | 几百个，只有那些Spring集成的 |
| 一致的命名约定| No | Yes |
| 质量保证| 依据规则。准确来讲，是作者的责任。 | 广泛的OSGi清单，Maven POM和Ivy元数据。Spring团队会解答QA |
| 托管| Contegix. 由Sonatype资助了多个镜像 | SpringSource资助的S3 |
| 搜索工具| 多种多样 | http://www.springsource.com/repository |
| 与SpringSource工具的集成| 通过STS和Maven依赖管理集成| 通过STS广泛的集成Maven、Roo、CloudFoundry |
