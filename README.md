# 


## June 2 2016 9:14 AM

# Threadpool

* * *


## system function/系统功能

Can loop through the thread pool, support pass function, pass, transfer call function, immediately terminate all threads, support thread recycling, save time and resources
可循环线程池，支持传函数、传参、传回调函数、立即终止所有线程，支持线程的循环利用，节省时间和资源

## Use examples/使用范例

```
pool = ThreadPoolSpark(pool_num)
for task in task_list:
    pool.run(func=func(), args=(self, task))
pool.wait()
```

## contact/联系方式


609610350@qq.com
