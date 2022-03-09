# test1
This is a test repository

![Mario](./Mario_NSMBW.png)


### 找檔案
:::info 
sudo find ./ -iname "\*abc\*" -type f
:::

```
sudo find ./ -iname "\*abc\*" -type f
```

### 找檔案內字串
:::info
sudo find "路徑" -iname "檔名" -type f -exec grep -nH "字串" {} \\;
或
sudo grep -nHr "字串" 路徑
:::

:::success
範例：
sudo find "/etc/" -iname "\*wpa\*" -type f -exec grep -nH "ssid" {} \\;
sudo grep -nHr "ssid" /etc/
:::

### BASH 顏色
:::info 
PS1='\e[0;36m\u\e[0m@\e[0;36m\w\e[0m> '
:::
