1. 先考虑 promise 中只封装同步操作的情况
2. 参照观察者模式，在 pending 状态中暂存回调
3. 链式调用
