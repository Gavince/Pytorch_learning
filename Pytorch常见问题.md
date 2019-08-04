1. ```
   Jacobian mismatch for output 0 with respect to input 0,
   numerical
   ```

   >[链接１](https://blog.csdn.net/wwyy2018/article/details/95106255)

2. ```
   AttributeError: cannot assign module before Module.__init__() call
   ```

   >调用了自定义的类，但是 在自定义的类的__init__函数下面没有写super( XXX, self ).__init__() 
   >
   >class XXX( nn.Module ):
   >    def __init__(self, 等等):
   >
   >​	super( XXX, self ).__init__()
   
3. ```
   RuntimeError: output with shape [1, 224, 224] doesn't match the broadcast shape [3, 224, 224]
   ```

   >[链接](https://blog.csdn.net/qq_31829611/article/details/90200694)

4. 