# date-format
时间格式化
引用：
import DateFormat from 'date-format-wgh';
const date=DateFormat("",5);
参数非必传，2个参数都不传默认为当前系统时间,默认为第三种格式
第一个参数，时间戳，如果取当前时间，传"",
第二个参数，格式化类型，总共6种类型，可传key，也可传值
1：YYYY-MM-DD
2：YYYY/MM/DD
3：YYYY-MM-DD hh:mm:ss
4：YYYY-MM-DD hh-mm-ss
5：YYYY/MM/DD hh:mm:ss
6：YYYY/MM/DD hh-mm-ss
