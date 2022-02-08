TS类型体操题：

1.还原Pick的功能。
typescript``` 
type MyPick<T, K extends keyof T> = { [V in K]: T[V] };
```
