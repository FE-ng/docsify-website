# 标题

这是一个 docsify 网站模版。
test docs

## 常见问题
git 开启git大小写敏感
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
  parent.getName?.()   // parent
  parent.getTitle?.()  //不会执
parent?.forEach()
parent?.map();