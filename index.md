## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Luliang931/Luliang931.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
### 对象拷贝 - 优雅的解决方案 Mapstruct
MapStruct GitHub 访问地址 : https://github.com/mapstruct/mapstruct/

使用例子 : github.com/mapstruct/m…

MapStrcut与其它工具对比以及使用说明! www.tuicool.com/articles/ui…

是否一直在使用BeanUtils.copyProperties 用于对象属性拷贝。 出现种种小问题。

会将同名属性拷贝到另外一个对象中，操作方便但是存在一个缺陷 （速度慢）
有些同名字段却无法进行特殊化处理，将会导致不想修改的字段被覆盖。也不能自定义属性映射
在 mvc层 我们经常会DTO对象返回给前端 进行字段渲染。我们不喜欢将所有字段都显示给前端，或者我们需要修改字段返回给前端，例如 数据中存储的上架下架是0，1  但是前端需要的字段是true 和 false。 我们都得进行手动判断处理然后编辑成DTO返回给前端
 MapStruct是一种类型安全的bean映射类生成java注释处理器。 我们要做的就是定义一个映射器接口，声明任何必需的映射方法。在编译的过程中，MapStruct会生成此接口的实现。该实现使用纯java方法调用的源和目标对象之间的映射，MapStruct节省了时间，通过生成代码完成繁琐和容易出错的代码逻辑。。

MapStruct 拥有的优点：

使用普通方法调用而不是反射来快速执行，他会在编译器生成相应的 Impl 方法调用时直接通过简单的 getter/setter调用而不是反射或类似的方式将值从源复制到目标
编译时类型安全性 : 只能映射彼此的对象和属性，不能将商品实体意外映射到用户 DTO等
在构建时清除错误报告，如 映射不完整 (并非所有目标属性都被映射) 或 映射不正确(无法找到适当的映射方法或类型转换)
MapStruct 提供的重要注解 :

@Mapper : 标记这个接口作为一个映射接口，并且是编译时 MapStruct 处理器的入口
@Mapping : 解决源对象和目标对象中，属性名字不同的情况
Mappers.getMapper 自动生成的接口的实现可以通过 Mapper 的 class对象获取，从而让客户端可以访问 Mapper接口的实现
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Luliang931/Luliang931.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
