# 開始這項目的編程



## 1. 打開工作項目

![Step1](img/3.png)

## 2. 打開 models 檔案

![Step1](img/4.png)


## 3. 加入以下代碼
```
class Wk(models.Model):
    yr = models.IntegerField()
    num = models.IntegerField()
    date1 = models.DateField('Date From')
    date2 = models.DateField('Date To')
    # https://www.epochconverter.com/weeks/2019
    # Week 01	December 31, 2018	January 6, 2019
```
