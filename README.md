# ecs

## Features

- [x] 系统基础信息查询[自研[basics](https://github.com/oneclickvirt/basics)、[gostun](https://github.com/oneclickvirt/gostun)]
- [x] IP基础信息并发查询[自研[basics](https://github.com/oneclickvirt/basics)]
- [x] CPU测试[自研[cputest](https://github.com/oneclickvirt/cputest)支持sysbench、geekbench、winsat]
- [x] 内存测试[自研[memorytest](https://github.com/oneclickvirt/memorytest)支持sysbench、dd]
- [x] 硬盘测试[自研[disktest](https://github.com/oneclickvirt/disktest)支持dd、fio、winsat]
- [x] 御三家流媒体解锁信息并发查询[借鉴[netflix-verify](https://github.com/sjlleo/netflix-verify)、[VerifyDisneyPlus](https://github.com/sjlleo/VerifyDisneyPlus)、[TubeCheck](https://github.com/sjlleo/TubeCheck)二次开发至于[CommonMediaTests](https://github.com/oneclickvirt/CommonMediaTests)]
- [x] 常见流媒体测试并发查询[自研代码，逻辑借鉴[RegionRestrictionCheck](https://github.com/lmc999/RegionRestrictionCheck)、[MediaUnlockTest](https://github.com/HsukqiLee/MediaUnlockTest)并自行修复错漏至于[UnlockTests](https://github.com/oneclickvirt/UnlockTests)]
- [x] IP质量/安全信息并发查询[自研，由于测试含密钥信息，故而私有化开发，但二进制文件编译至于[securityCheck](https://github.com/oneclickvirt/securityCheck)]
- [x] 邮件端口测试[自研[portchecker](https://github.com/oneclickvirt/portchecker)]
- [x] 三网回程测试[借鉴[zhanghanyun/backtrace](https://github.com/zhanghanyun/backtrace)二次开发至于[oneclickvirt/backtrace](https://github.com/oneclickvirt/backtrace)]
- [x] 三网路由测试[借鉴[NTrace-core](https://github.com/nxtrace/NTrace-core)二次开发至于[nt3](https://github.com/oneclickvirt/nt3)]

## TODO

- [ ] 测试网速[借鉴[speedtest-go](https://github.com/showwin/speedtest-go)二次开发]

## 说明

开发中，勿要使用