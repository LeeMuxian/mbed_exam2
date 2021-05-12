# mbed_exam2

我用一個RPC呼叫我的gesture detection的模式，我在這個模式函式中使用兩個thread，一個去偵測手勢，另一個是得到feature。
我的feature是先判斷有沒有加速度值超過threshold angle(30度和80度)，小於30度者為circle，介於中間者為slope，大於80度者為shake。
