# date-format
时间格式化</br>
引用：</br>
import DateFormat from 'date-format-wgh';</br>
const date=DateFormat("",5);</br>
参数非必传，2个参数都不传默认为当前系统时间,默认为第三种格式</br>
第一个参数，时间戳，如果取当前时间，传"",</br>
第二个参数，格式化类型，总共6种类型，可传key，也可传值</br>
1：YYYY-MM-DD</br>
2：YYYY/MM/DD</br>
3：YYYY-MM-DD hh:mm:ss</br>
4：YYYY-MM-DD hh-mm-ss</br>
5：YYYY/MM/DD hh:mm:ss</br>
6：YYYY/MM/DD hh-mm-ss</br>
