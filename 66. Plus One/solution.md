# 加一
## 1. 数学方法
· 在最后一个位置加一，用一个bool值记录是否进位；
· 从最后一个位置开始遍历，如果数字大于9则说明需要进位，记录bool值为true，如果一个数字小于等于9则说明不需要进位，记录bool值为false；
· 在循环结束后查看是否会因为进位而导致多出一位，若多出来一位则插入一个新位置。