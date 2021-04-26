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
