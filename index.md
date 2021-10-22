## Foundamental Of Python

### Python 語言特色
* 高階語言：Python 是一種高階程式語言，撰寫程式時不需要考量低階語言等細節，如管理記憶體、位址等等
* 直譯式語言：Python 語言寫的程式不需要翻譯二進制代碼，且可以直接使用原始碼運行。
* 多樣的模組：提供多樣的內建模組，在做其他工作時，嵌入性高，運用彈性也很高。

### 變數(Variable) 

變數又分為數值變數(如1,2,3)以及字串變數(如Project,Issues)
且使用變數的階段不需要宣告資料的型態，Python 將會偵測變數值設定對應的資料型態
  >Python一樣特色為不需要宣告就可以使用

    變數名稱 = 變數值

設變數名稱X的值為10(數值變數)
    
    X = 10

如果設定多個值，可以用'='一同指定，如：

    X = Y = Z  = 10
    
設定變數名稱Sport的值為羽毛球，如：
    
    sport = "桌球"
    
同一行設定多個變數

    weight,height = 50,"身高"

刪除變數
    
    del sport
 
### 變數命名規則
* 變數名稱第一個字母不得為數字
* 大小寫區分
* 只能由大小寫字母、數字、_、組成變數名稱
* 不能與Python保留字相同

Python 保留字
  <table>
      <tr>
          <td>and</td>
          <td>as</td>
          <td>assert</td>
          <td>async</td>
          <td>await</td>
          <td>break</td>
      </tr>
      <tr>
          <td>class</td>
          <td>continue</td>
          <td>def</td>
          <td>del</td>
          <td>elif</td>
          <td>else</td>
      </tr>
      <tr>
          <td>except</td>
          <td>finally</td>
          <td>for</td>
          <td>from</td>
          <td>global</td>
          <td>if</td>
      </tr>
      <tr>
          <td>import</td>
          <td>in</td>
          <td>is</td>
          <td>lambda</td>
          <td>nonlocal</td>
          <td>not</td>
      </tr>
      <tr>
          <td>or</td>
          <td>pass</td>
          <td>raise</td>
          <td>return</td>
          <td>try</td>
          <td>while</td>
      </tr>
      <tr>
          <td>with</td>
          <td>yield</td>
          <td>False</td>
          <td>None</td>
          <td>True</td>
          <td></td>
      </tr>
  </table>

### 各樣的數值型態

#### 整數、浮點數資料型態

  >Python的註解符號為"#"，執行時會跳過#後面的符號
  
    number_1 = 10 #整數(int)
    number_2 = 1.5 #浮點數(float)
    
整數值若要設定為浮點數，可加上小數點符號

    number_3 = 20.0
    
#### 布林型態(F、T為大寫)

    bool = True
    bool = False

#### 字串

    string = "資工具人"
    
若字串中本身包含雙引號則用單引號去包覆，如：
    
    string_1 = '資工具人說："嗨!需要幫忙嗎?"'

#### 換行符號
    鍵盤中的反斜線+n
    
    string_2 = "要吃早餐嗎 \n沒有的話我晚點再問一次"

### 函數

#### print()
print 函數可以列印出指定項目的內容，是最常見的語法之一，其語法如下：
    
    print(100)
    print("今晚打老虎")
    print(Taiwan's country code is 886)

#####參數格式化

print() 支援參數格式化的功能，如"%s"為字串"%d"為整數"%f"為浮點數，其語法如下：
    
    print(項目%(參數))
    name = "小白"
    height = 180
    print("%s的身高是%d"%(name,height)) #小白的身高是180

##### 控制列印位置

參數格式化可以精準的控制函數列印出的位置，讓想輸出的內容可以整齊排列
* %5d 固定列印5個字元，若少於五位數，程式將在左方填入空白字元
* %5s 固定列印5個字元，若字串少於五個位元，會在字串左方填入空白字元
* %9.2f 固定列印9個字元，小數點固定兩個字元
* 
#### type()
type 函數會取得項目的資料型態，其語法如下：
    
    print(type(100))    #<class 'int'>
    print(type(True))   #<class 'bool'>
    print(type("hello"))    #<class 'str'>
    print(type(3.14))   #<class'float'>
    
You can use the [editor on GitHub](https://github.com/N3824jx4bp6/Teaching/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/N3824jx4bp6/Teaching/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
