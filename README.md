### calcylation.js小数计算
1. compute 用于两个小数进行计算
   `compute(num1: number, num2: number, symbol: Symbol)`

2. calculate 多个数进行计算 使用方法（calculate`${num1} + ${num2} - ${num3}`）
   `calculate = function (arg0: any, ...args: any)`

3. toFixed 保留小数位，不进行四舍五入操作
   `toFixed = (num: number, len: number)`

   

### gulp-public.js 项目自动上传到服务器

gulp的task方法通过ssh协议连接服务器，ftp协议上传文件
