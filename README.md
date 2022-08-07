# 学习*markdown*语法

---

### 简介 
+ markdown可以通过编码的方式快速设计界面、布局美观的文档
+ markdown的语法包括有：标题、段落、区块引用、代码区块、列表、强调、分割线、链接、链接图片、反斜杠转义符`\`、符号'\`'

### *markdown* 使用、效果、注意事项

1. 标题

    1.1. 一级、二级标题可以使用`=` 或者 `-`
    1.2. 也可以使用`#` 其数量就代表几级标题   
    1.3. 举例 三级标签这样表示：### 我是三级标题
    ### 我是三级标题
    
    
2. 段落

   要创建段落，请使用空白行将一行或多行文本进行分隔。

3. 区块引用

   3.1. 要创建区块引用需要段落前加上 `>`,例如：
   
      > 我是一级区块引用
   
   3.2. 区块引用支持嵌套, 例如:
      > 我是一级区块引用
      >> 我是二级区块引用
      >>> 我是三级区块引用
      >>>>...
      
      以此类推
      
      
4. 代码区块

   创建代码区块可以使用四个空格、一个制表符或者使用三个反引号（```）或      三个波浪号（~~~）。
   举例：
   
   ``` 
   public class Test {
     public static void main (String [] args) {
       System.out.print("Hello,Markdown.")
     }
   }
   
5. 强调
   
    又分为斜体、粗体、粗斜体
    
    5.1. 创建斜体使用`*需要斜体的内容*`,例如
    
      > 我是一段*文字*
    
    5.2. 创建粗体使用`**需要加粗的内容**`,例如
    
      > 我是一段**文字**
    
    5.3. 创建粗斜体使用`***需要粗斜体的内容***`,例如
    
      > 我是一段***文字***
        
    5.4. 补充由于还可以使用`--`、`-`、`---`等符号来创建上述强调，但是此对只能针对左右有空格的内容才有效，所以未举例
    
6. 列表

    又分为有序列表、无序列表
    
    6.1. 有序列表
    
    创建有序列表需要使用数字后面紧跟一个英文句点，数字不一定要有序，因为一般编辑器会自动排序，例如 `1. 内容 ....`
    
   *markdown* 语法
   ``` 
    > 1. 第一项
    > 6. 第二项
    > 3. 第三项
    >     1. 第三项的第一子项
    ```
    预览效果
    
    > 1. 第一项
    > 6. 第二项
    > 3. 第三项
    >     1. 第三项的第一子项
    6.2. 无序列表
    
    创建无序列表可以使用`*`、`-`、`+`
    
    *markdown* 语法
    ```
    > - 第一项
    > - 第二项
    > - 第三项
    >     - 第三项的第一个子项
    ```
    
    预览效果
    
    > - 第一项
    > - 第二项
    > - 第三项
    >     - 第三项的第一个子项
    
7. 链接

   *markdown* 语法
   
    
   
    ```
    
    [超链接显示名](超链接地址 "超链接title")
    [点击跳转到百度](https://www.baidu.com "百度")
    
    ```
    
    预览效果
    
    [点击跳转到百度](https://www.baidu.com "百度")
    
8. 图片
  
  *markdown* 语法
  
  ```
  ![图片alt](图片链接 "图片title")
  
  ```
  
  预览效果
  
  ![点击跳转到百度](图片链接 "百度")
  
  
9. 反斜杠转义符`\`

    相当于反转义作用。使符号成为普通符号。
    
    
 10. 符号'\`'
     
     起到标记作用。如：
     
     *markdown* 语法
     > \`ctrl+a\`
     
     预览效果
     
     > `ctrl+a`

  
