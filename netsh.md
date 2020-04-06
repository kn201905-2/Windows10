# パワーシェル  
参考 URL:  
https://www.colorconsole.de/cmd/jp/Windows_7/netsh.htm

* インタフェイス名の確認
```
> netsh interface show interface
```

* IPv6 アドレスの付加
```
> netsh interface ipv6 add address {インタフェイス名} {fe80::1:2/64} [active | persistent]
```

