# nrm/yrm
> 建议安装yrm ,可以修改yarn,nrm不可以，yrm 与nrm commond 一致
## 安装
```bash
 npm i -g nrm
```

## 查看包源
> 或者通过 nrm current 命令查看当前源的名称
```bash
nrm ls
```
* npm -------- https://registry.npmjs.org/
  yarn ------- https://registry.yarnpkg.com/
  cnpm ------- http://r.cnpmjs.org/
  taobao ----- https://registry.npm.taobao.org/

## 切换包源
> 例如 nrm use npm
```bash
nrm use <registry>
```

## 添加包源
```bash
nrm add <registry> <url>
```

## 删除包源
```bash
nrm del <registry>
```

## 测试包源响应时间
```bash
nrm test <registry>
```