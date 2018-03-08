# Set & Map

## Set

```javascript
const set = new Set([]); // 接受具有 iterable 接口的期货数据结构 
set.size;
set.add(value); // return set;
set.delete(value); // return boolean;
set.has(value); // return boolean;
set.clear(); // return undefined;

// 遍历方法
set.keys();
set.values();
set.entries();
set.forEach();
```

## WeakSet

WeakSet 结构与 Set 类似，也是不重复的值的集合。但是，它与 Set 有两个区别。

首先，WeakSet 的成员只能是对象，而不能是其他类型的值。

其次，WeakSet 中的对象都是弱引用，即垃圾回收机制不考虑 WeakSet 对该对象的引用，也就是说，如果其他对象都不再引用该对象，那么垃圾回收机制会自动回收该对象所占用的内存，不考虑该对象还存在于 WeakSet 之中。

```javascript
WeakSet.prototype.add(value)：向 WeakSet 实例添加一个新成员。
WeakSet.prototype.delete(value)：清除 WeakSet 实例的指定成员。
WeakSet.prototype.has(value)：返回一个布尔值，表示某个值是否在 WeakSet 实例之中。
```

## Map

```javascript
const map = new Map();
map.size;
map.set(key, value); // return map;
map.get(key); // return value;
map.has(key); // return boolean;
map.delete(key); // return boolean;
map.clear(); // return undefined;

// 遍历方法
map.keys()
map.values()
map.entries()
map.forEach()
```

## WeakMap

WeakMap 只接受对象作为键名（null 除外），不接受其它类型的值作为键名。

WeakMap 的设计目的在于，有时我们想在某个对象上面存放一些数据，但是会形成对于这个对象的引用。一旦不再需要这两个对象，我们就必须手动删除这个引用，否则垃圾回收机制就不会释放其占用的内存。

```javascript
const wm = new WeakMap();
wm.get();
wm.set();
wm.has();
wm.delete();
```

