# noa_pac——An Entis GLS Engine archive (un)packer



## Quick Start

```cmd
chcp 932
noa32c.exe /p /d "/path/to/input/*" "/path/to/output/fname.noa"
```



A possible file tree would be like:

```
example
├─ noa32c.exe
├─ output
│  └─ my_pack.noa
└─ input
   ├─ 1_scene01.srcxml
   ├─ 1_scene02.srcxml
   └─ 1_scene03.srcxml
```



## Advance

```
noa32c[/nologo] {/p|/x|/c} [/r]
[/pass <password>] [/gp] [/l <list-file>] [/d]
[/raw] [/erisa] [/crypt] [/erisa_crypt] [/time]
[<source-file>] <destination>
```



| Option  | Note               |
| ------- | ------------------ |
| /nologo | no title           |
| /p      | pack (.noa) file   |
| /x      | unpack (.noa) file |
|         |                    |





## Refenrence

https://forums.fuwanovel.moe/topic/22068-help-regarding-noa-archives/
