# zipObject<Value>

> - `description`: 第一个数组是对象的key, 第二个数组是对象的value
> - `param` `props` `(string|number)[]`
> - `param` `values` `Value[]`
> - `returns` {ObjectType<Value>}
> - `version`: 2.1.11
: ```ts
 zipObject(['a', 'b'], [1, 2]) 
 => { 'a': 1, 'b': 2 }
 ```
 