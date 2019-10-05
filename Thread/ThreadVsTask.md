**Разница между Task и Thread**

**Thread** - неспосредственнно поток ОС. Позволяют больше контролировать их (Abort, Suspend, Resume)

**Task** - класс из Task Parallel Library. Как и ThreadPool, Task не создает собственный ОС поток. Вместо этого Task исполняться с помощью TaskScheduler. default scheduler - просто запускает задачи на threadPool. Но в отличии от threadPool, мы можем определить когда  завершилась задача и вернуть результат.