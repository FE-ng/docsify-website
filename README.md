# 标题

这是一个 基于 docsify + vercel + github 搭建的个人博客。
用以记录自己的成长、曾经遇见的 bug 和积累;

## 常见问题

git 开启 git 大小写敏感
git config core.ignorecase false

## 处理后端数据循环问题

let parent = {
name: "parent",
friends: ["p1", "p2", "p3"],
getName: function() {
console.log(this.name)
},
forEach: () => {console.log('custom forEach')}
};

parent.map?.()
parent.getName?.() // parent
parent.getTitle?.() //不会执
parent?.forEach()
parent?.map();
