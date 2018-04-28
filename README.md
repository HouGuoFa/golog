### 什么是golog
- golog是基于golang语言的一个日志库



### 如何使用
- 导入golang到你的项目中, 就像导入一个标准库一样
- 通过初始化函数对日志打印级别进行初始化, 然后再你的代码的任意位置进行调用


### 样例

```
    func main() {
    	
    	golog.SetLevel(golog.LevelInfo)
    	
    	# debug级别日志
    	golog.Debug("日志库初始化设置成功~") 
    
    	# info级别日志
    	golog.Info("日志库初始化设置成功~") 
    	
    	# error级别日志
    	golog.Error("日志库初始化设置成功~")
        
    	# warn级别日志
    	golog.Warn("日志库初始化设置成功~") 
    	
    	# critical级别日志
    	golog.Critical("日志库初始化设置成功~") 
    }
    
```


