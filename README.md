# test1
This is a test repository

### 找檔案
```
sudo find ./ -iname "\*abc\*" -type f
```

```
sudo find ./ -iname "\*abc\*" -type f
```

### 找檔案內字串
```
sudo find "路徑" -iname "檔名" -type f -exec grep -nH "字串" {} \\;
或
sudo grep -nHr "字串" 路徑
```

```
範例：
sudo find "/etc/" -iname "\*wpa\*" -type f -exec grep -nH "ssid" {} \\;
sudo grep -nHr "ssid" /etc/
```

### BASH 顏色
```
PS1='\e[0;36m\u\e[0m@\e[0;36m\w\e[0m> '
```


![Mario](./Mario_NSMBW.png)

