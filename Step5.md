# 課後要求

- 頁面的訪問路徑是 http://127.0.0.1:8000/ww2/
- 代碼上傳到各自的  misdj-ww
- 步骤提示

  - urls 裡的 path('ww2/', views.ww2, name='ww2'),
  - views 裡的 def ww2(request):
  - templates 裡的 ww2.html
    - 日期要格式為 2019-01-09，請參考  https://docs.djangoproject.com/en/2.2/ref/templates/builtins/#std:templatefilter-date
  - templates 裡的 base.html 要加 Style 才能有美觀的表格

![Step1](img/51v2.png)


## path 請注意 要有 /，這個習慣可以省掉日後的一些麻煩。
![Step1](img/52.png)