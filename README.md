# xmlparase
```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE bookstore SYSTEM "book.dtd">
<bookstore>  
    <book id="book1">  
        <name>Java 核心技术</name>  
        <author>Cornell </author>  
        <year>2014</year>  
        <price>89</price>  
    </book>  
    <book id="book2">  
        <name>深入浅出MyBatis</name>  
        <author>杨开振</author>  
        <year>2016</year>  
        <price>69</price>  
    </book>  
    <book id="book3">  
        <name>Java RESTful Web Service实战</name>  
        <author>韩陆</author>  
        <year>2016</year>  
        <price>59</price>
    </book>  
</bookstore> 
```
- 通过自己编写DTD来定义上述XML文档
- 通过DTD文件，DOM解析并验证上述XML文档，并将上述xml文档转为java对象
