# 中日英自然码（带辅码）双拼输入法

根据本人习惯定制，**适合轻度依赖辅码同时有英文日文输入需求的自然码双拼输入法用户**。经实测，中英日三语输入几乎不存在冲突和干扰的情况，因为双拼、英文、日文的编码差距较大，往往在键入三个字母时，即能判定输入的是中文、英文还是日文。

## 2019.01.21 更新英文词库

原来的英文词库只有5.6万词汇量，新版的英文词库扩大了近 10 倍，达到词汇 47.9 万词。来源：https://github.com/dwyl/english-words 。

## 特征

### 1. 支持辅码和扩展词库

#### 1) 支持**非完全匹配**的辅码

使用的是 Github 用户 @henices 制作的「自然码 2000」方案的带辅码码表。但 zrm2000.schema.yaml 经过本人微调，如需原版请至 @henices 的相关页面下载。**非完全匹配**是指，不会像单独使用「自然码 2000」方案那样精确使用码表，但键入辅码时仍然会出现在选词列表中。

如输入 tamfr，「他们」一词即处在候选词第一位：

<img width="528" height="390" src="https://raw.githubusercontent.com/lippmann/lrime/master/Samples%20screenshots/%E5%B8%A6%E8%BE%85%E7%A0%81%E8%87%AA%E7%84%B6%E7%A0%81%E7%A4%BA%E4%BE%8B.png"/>

如果你对词库的要求不高，建议使用 「自然码 2000」方案，而不是本方案。
  
#### 2) 支持 luna_pinyin 外挂词库

### 2. 支持英文和日文联想输入

#### 1) 英文输入

词库来自 Rime 中的 easy english 输入法词库。支持单词自动补全，但不支持语句输入。

<img width="528" height="390" src="https://raw.githubusercontent.com/lippmann/lrime/master/Samples%20screenshots/%E8%8B%B1%E6%96%87%E8%81%94%E6%83%B3%E8%BE%93%E5%85%A5%E6%B3%95%E7%A4%BA%E4%BE%8B.png"/>

#### 2) 日文输入

日文输入法来自 @天珩 设计的「nihongo-r」日文输入方案。由于 GitHub 不支持 25M 以上文档，故日文输入法词典文件为压缩包。支持单语自动补全，但不支持语句输入。

<img width="528" height="390" src="https://raw.githubusercontent.com/lippmann/lrime/master/Samples%20screenshots/%E6%97%A5%E6%96%87%E8%81%94%E6%83%B3%E8%BE%93%E5%85%A5%E6%B3%95%E7%A4%BA%E4%BE%8B.png"/>

##### 日文输入法特殊符号输入方式

つ → tsu、ん → n、片假名长音ー → q、促音っ → t


## 链接

带辅码自然码方案「自然码 2000」：https://github.com/henices/rime


## 鸣谢

1. Rime 输入法开发者 @佛振 先生及所有贡献者；
2. 自然码输入法开发者 @周志农 先生；
3. Rime 版带辅码自然码方案「自然码 2000」的制作者 @henices ；
4. Rime 版 nihongo-r 日文输入方案的制作者 @天珩。
5. 英文词库来自 GitHub 用户 @dwyl。
