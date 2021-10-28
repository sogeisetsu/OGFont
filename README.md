# OUR GREAT FONTS

![](https://suyuesheng-biaozhun-blog-tupian.oss-cn-qingdao.aliyuncs.com/blogimg/20211026233546.JPG)

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

这是优秀开源字体收集仓库。面对当前严峻的版权形式，收集免费开源可商用的字体，致力于让世界更加美好，让开发者有效规避版权纠纷。本仓库所收集之字体为网络上开源字体，所选用字体的版权声明清晰明确，所收集之字体相关的开源协议会在/credit文件夹放置。

## 目录

- [安全](#安全)
  - [开源字体使用注意事项](#开源字体使用注意事项)

- [Background](#Background)
- [Usage](#Usage)
  - [本仓库所含字体名称](#本仓库所含字体名称)
- [伟大的Unicode](#伟大的Unicode)
  - [中日韩统一表意文字](#中日韩统一表意文字)
- [字体收录规则](#字体收录规则)
- [徽章](#徽章)
- [维护者](#维护者)
- [致谢](#致谢)
- [如何贡献](#如何贡献)
- [LICENSE](#LICENSE)

## 安全

……

### 开源字体使用注意事项

……

## Background

……

## Usage

~~在`css`文件中加入~~，因为访问`raw.gitee`的时候会面临返回的`content-type`为`text/plain`。所以在前端文件中引入`raw.gitee`的文件链接会失效。目前有效的解决办法有这么几个：

1. 开通`gitee page`然后通过访问`gitee page`内的文件链接可以解决这个问题。目前本仓库还没有开通`gitee page`的打算。需要使用的朋友可以fork本仓库进行开通`gitee pages`来调用`css`文件。
2. 使用服务器厂商提供的对象存储服务，这个一般是收费的。

我目前的方案~~是使用阿里云的`oss`服务，大家可以调用我托管在阿里云`oss`的`css`文件。~~是将仓库转移到GitHub，然后用[jsDelivr](https://www.jsdelivr.com/)进行国内的CDN加速。本仓库所有文件的cdn地址为[sogeisetsu/OGFont CDN by jsDelivr - A CDN for npm and GitHub](https://www.jsdelivr.com/package/gh/sogeisetsu/OGFont)。

- *失效方式*

  ```css
  @import url("https://gitee.com/sogeisetsu/myfont/raw/master/myfont.css");
  ```

- 有效方式（停止支持）

  ```css
  @import url("https://suyuesheng-biaozhun-blog-tupian.oss-cn-qingdao.aliyuncs.com/font/font.css");
  ```

- 有效方式（推荐）

  ```css
  @import url("https://cdn.jsdelivr.net/gh/sogeisetsu/OGFont@0.1.0/myfont.min.css");
  ```

  

### 本仓库所含字体名称

英文名和中文名具是字体文件中所声明的官方名称，只要字体所包含的汉字包含了大部分中日韩表意文字，即在汉字一栏以`CJK`标注。

| 英文名              | 中文名     | LICENSE                                      | 特色                                                         | 汉字 | 英文字母 |
| ------------------- | ---------- | -------------------------------------------- | ------------------------------------------------------------ | ---- | -------- |
| `unifont`           |            | GNU General Public License version 2         | 点阵正黑，覆盖`unicode`较全。适合生僻字和像素风格。          | CJK  | ✔        |
| `unifont-jp`        |            | GNU General Public License version 2         | 点阵正黑，覆盖`unicode`较全。适合生僻字和像素风格。汉字是日文汉字风格。 | CJK  | ✔        |
| `WenQuanYi Zen Hei` | 文泉驿正黑 | GPL v2 license with font embedding exception | 诸多Linux发行版默认中文字体，字体偏小时会模糊发虚。建议当中文标题使用。 | CJK  | ✔        |

## 伟大的Unicode

……

[ttf ttc otf otc 这些字体究竟有什么区别？ - OttoLi 的胡言乱语](https://www.ottoli.cn/study/fonts#wei_tu_he_shi_liang_tu)

[字符编码笔记：ASCII，Unicode 和 UTF-8 - 阮一峰的网络日志 (ruanyifeng.com)](https://www.ruanyifeng.com/blog/2007/10/ascii_unicode_and_utf-8.html)

### 中日韩统一表意文字

……

[中日韩统一表意文字 - 维基百科，自由的百科全书 (wikipedia.org)](https://zh.wikipedia.org/wiki/中日韓統一表意文字)

## 字体收录规则

![](https://suyuesheng-biaozhun-blog-tupian.oss-cn-qingdao.aliyuncs.com/blogimg/20211026235738.JPG)

## 徽章

**如果您的作品使用的字体全部都被本仓库收录，推荐您将下列徽章之一添加到您的作品。**

![Our Great Fonts: open source fonts (shields.io)](https://img.shields.io/badge/Our%20Great%20Fonts-open%20source%20fonts-green)
![Our Great Fonts: 采用开源字体 (shields.io)](https://img.shields.io/badge/Our%20Great%20Fonts-%E9%87%87%E7%94%A8%E5%BC%80%E6%BA%90%E5%AD%97%E4%BD%93-green)

复制以下代码到你的网址，让访问者知道你使用的是优秀的可商用开源字体。

```html
<a href="https://gitee.com/sogeisetsu/myfont">
<img alt="Our Great Fonts" style="border-width:0" src="https://img.shields.io/badge/Our%20Great%20Fonts-%E9%87%87%E7%94%A8%E5%BC%80%E6%BA%90%E5%AD%97%E4%BD%93-green" />
</a><br>
本作品所使用字体为<a href="https://gitee.com/sogeisetsu/myfont">免费可商用字体</a>
```

## 维护者

……

## 致谢

……

## 如何贡献

……

## LICENSE

[GPL-3.0](https://gitee.com/sogeisetsu/myfont/blob/master/LICENSE) © 2021 苏月晟。



