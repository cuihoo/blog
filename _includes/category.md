分类：｛｛ page.name ｝｝
文章数：｛｛ site.categories[page.name] | size ｝｝
列表：
｛％ for post in site.categories[page.name] ％｝
//和读取post一样
｛％ endfor ％｝
