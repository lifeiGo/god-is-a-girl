###### 用扩展运算符

```
let b = [{a:1,c:2},{a:2,c:3},{a:1,c:2}]
//想要深拷贝b用的方法
let d = [...b]
```

###### 数组最后一项加值

```
let arr = [a,b];
arr.push('3')
//push 的方法更好一些 
arr[length] = 3
```

###### function的参数应用展开运算符 更加的完美

    //good
    function getFullName(user) {
      const { firstName, lastName } = user;
      return `${firstName} ${lastName}`;
    }

    // best
    function getFullName({ firstName, lastName }) {
      return `${firstName} ${lastName}`;
    }

###### 尽量的是少用eval因为他打开了太多的漏洞



