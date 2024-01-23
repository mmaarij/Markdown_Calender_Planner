# mdcal

Generate calendar in Markdown table. Written in Python3.

## Usage

Generate calendar of current month:

```sh
$ python3 mdcal.py
2019/10

# January 2024

|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|[1](#01-01-2024)|[2](#02-01-2024)|[3](#03-01-2024)|[4](#04-01-2024)|[5](#05-01-2024)|[6](#06-01-2024)|[7](#07-01-2024)|
|[8](#08-01-2024)|[9](#09-01-2024)|[10](#10-01-2024)|[11](#11-01-2024)|[12](#12-01-2024)|[13](#13-01-2024)|[14](#14-01-2024)|
|[15](#15-01-2024)|[16](#16-01-2024)|[17](#17-01-2024)|[18](#18-01-2024)|[19](#19-01-2024)|[20](#20-01-2024)|[21](#21-01-2024)|
|[22](#22-01-2024)|[23](#23-01-2024)|[24](#24-01-2024)|[25](#25-01-2024)|[26](#26-01-2024)|[27](#27-01-2024)|[28](#28-01-2024)|
|[29](#29-01-2024)|[30](#30-01-2024)|[31](#31-01-2024)|||||
## 01-01-2024
## 02-01-2024
## 03-01-2024
## 04-01-2024
## 05-01-2024
## 06-01-2024
## 07-01-2024
## 08-01-2024
## 09-01-2024
## 10-01-2024
## 11-01-2024
## 12-01-2024
## 13-01-2024
## 14-01-2024
## 15-01-2024
## 16-01-2024
## 17-01-2024
## 18-01-2024
## 19-01-2024
## 20-01-2024
## 21-01-2024
## 22-01-2024
## 23-01-2024
## 24-01-2024
## 25-01-2024
## 26-01-2024
## 27-01-2024
## 28-01-2024
## 29-01-2024
## 30-01-2024
## 31-01-2024
***


** Process exited - Return Code: 0 **
Press Enter to exit terminal

```

Generate calendar of specified year:

```sh
$ python3 mdcal.py 2019
2019/1

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|1|31|1|2|3|4|5|6|
|2|7|8|9|10|11|12|13|
|3|14|15|16|17|18|19|20|
|4|21|22|23|24|25|26|27|
|5|28|29|30|31|1|2|3|

2019/2

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|5|28|29|30|31|1|2|3|
|6|4|5|6|7|8|9|10|
|7|11|12|13|14|15|16|17|
|8|18|19|20|21|22|23|24|
|9|25|26|27|28|1|2|3|

2019/3

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|9|25|26|27|28|1|2|3|
|10|4|5|6|7|8|9|10|
|11|11|12|13|14|15|16|17|
|12|18|19|20|21|22|23|24|
|13|25|26|27|28|29|30|31|

2019/4

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|14|1|2|3|4|5|6|7|
|15|8|9|10|11|12|13|14|
|16|15|16|17|18|19|20|21|
|17|22|23|24|25|26|27|28|
|18|29|30|1|2|3|4|5|

2019/5

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|18|29|30|1|2|3|4|5|
|19|6|7|8|9|10|11|12|
|20|13|14|15|16|17|18|19|
|21|20|21|22|23|24|25|26|
|22|27|28|29|30|31|1|2|

2019/6

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|22|27|28|29|30|31|1|2|
|23|3|4|5|6|7|8|9|
|24|10|11|12|13|14|15|16|
|25|17|18|19|20|21|22|23|
|26|24|25|26|27|28|29|30|

2019/7

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|27|1|2|3|4|5|6|7|
|28|8|9|10|11|12|13|14|
|29|15|16|17|18|19|20|21|
|30|22|23|24|25|26|27|28|
|31|29|30|31|1|2|3|4|

2019/8

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|31|29|30|31|1|2|3|4|
|32|5|6|7|8|9|10|11|
|33|12|13|14|15|16|17|18|
|34|19|20|21|22|23|24|25|
|35|26|27|28|29|30|31|1|

2019/9

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|35|26|27|28|29|30|31|1|
|36|2|3|4|5|6|7|8|
|37|9|10|11|12|13|14|15|
|38|16|17|18|19|20|21|22|
|39|23|24|25|26|27|28|29|
|40|30|1|2|3|4|5|6|

2019/10

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|40|30|1|2|3|4|5|6|
|41|7|8|9|10|11|12|13|
|42|14|15|16|17|18|19|20|
|43|21|22|23|24|25|26|27|
|44|28|29|30|31|1|2|3|

2019/11

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|44|28|29|30|31|1|2|3|
|45|4|5|6|7|8|9|10|
|46|11|12|13|14|15|16|17|
|47|18|19|20|21|22|23|24|
|48|25|26|27|28|29|30|1|

2019/12

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|48|25|26|27|28|29|30|1|
|49|2|3|4|5|6|7|8|
|50|9|10|11|12|13|14|15|
|51|16|17|18|19|20|21|22|
|52|23|24|25|26|27|28|29|
|1|30|31|1|2|3|4|5|
```

Generate calendar of specified month:

```sh
$ python3 mdcal.py 1970 1
1970/1

|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|29|30|31|1|2|3|4|
|5|6|7|8|9|10|11|
|12|13|14|15|16|17|18|
|19|20|21|22|23|24|25|
|26|27|28|29|30|31|1|
```

## Rendered Example

2019/10

|Week|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|40|30|1|2|3|4|5|6|
|41|7|8|9|10|11|12|13|
|42|14|15|16|17|18|19|20|
|43|21|22|23|24|25|26|27|
|44|28|29|30|31|1|2|3|
