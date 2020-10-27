### 1.使用python3 中pip 安装 selenium 
```text
  python3 -m pip install selenium

```
### 2.安装 ChromeDriver  
- Chrome：http://chromedriver.storage.googleapis.com/index.html

```text
    1.将下载的chromeDriver放在 /usr/local/bin/ 下
    mv chromeDriver /usr/local/bin/chromeDriver
```

### 使用步骤：
```text
    1、按格式输入商品链接和开售时间
    2、程序自动打开chrome浏览器访问链接，跳至登陆页面请在30秒内扫码登陆
    3、跳至商品页面请在开售时间前选择所有商品规格（如鞋码、配色）
    4、开售后自动下单，在淘宝规定时间内完成支付
    
    提示：
    
    1、必须配合chrome浏览器（71-73版本）使用,只适用于淘宝和天猫
    2、开售时间格式必须正确（xxxx-xx-xx(空格)xx:xx:xx）
    4、扫码登陆后，chrome浏览器可能会拦截重定向请求，如发生请在浏览器地址栏末尾收到跳转网页
    5、跳至商品页面，必须在开售时间前完成 全部 商品规格选择
    6、提前设置默认邮寄地址和电话，中途无法更改
    7、无法在下单页面操作，不适用使用优惠券等情况
```