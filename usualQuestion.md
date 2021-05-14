## 常见问题

git 开启 git 大小写敏感
git config core.ignorecase false

## 处理后端数据循环问题

```typescript
let parent = {
  name: 'parent',
  friends: ['p1', 'p2', 'p3'],
  getName: function () {
    console.log(this.name);
  },
  forEach: () => {
    console.log('custom forEach');
  },
};
parent.map?.();
parent.getName?.(); // parent
parent.getTitle?.(); //不会执
parent?.forEach();
parent?.map();
```

## plop .hbs handlebars 模板

handlebars 模板和 react JSX 语法一起使用时 添加模板变量可以用\进行转译

```tsx
pagination=\{{
  showQuickJumper: true,
  showSizeChanger: true,
  current: pagination.page,
  total: pagination.total,
  pageSize: pagination.pageSize,
  pageSizeOptions: baseTableConf.pageSizeOptions,
  onChange: handleChangePage,
}}
```

## 错误处理

和后端进行对接完成 时不时会出现后端将[]返成{}的情况
这就导致了前端如果没有做好数据容错极其容易发生页面崩溃等 P0 级别的影响
而前端要做到数据容错 以往都是判断某个变量是否是数组 然后再调用 map 等迭代方法

```tsx
Array.isArray(temp) && temp.map((i) => doSomething(i));
```

其实是比较复杂并且判断起来很吃力的
但是因为哟可选链的加入(?.)
上面的写法可以简化为

```tsx
temp.map?.((i) => doSomething(i));
```

之前都只是简单的使用可选链去获取对象 value,但是文档里面写的很清楚可以用于函数!
