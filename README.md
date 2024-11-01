# noa_pac——An Entis GLS Engine archive (un)packer



## Quick Start

### 1. How to pack

```cmd
chcp 932
noa32c.exe /p /d "/path/to/input/*" "/path/to/output/fname.noa"
```

A possible file tree would be like:

```
example_pack
├─ noa32c.exe
├─ output
│  └─ my_pack.noa
└─ input
   ├─ 1_scene01.srcxml
   ├─ 1_scene02.srcxml
   └─ 1_scene03.srcxml
```

### 2. How to unpack

```cmd
chcp 932
noa32c.exe /x "/path/to/input/fname.noa" "/path/to/output/"
```

A possible file tree would be like:

```
example_unpack
├─ noa32c.exe
├─ input
│  └─ my_pack.noa
└─ output
   ├─ 1_scene01.srcxml
   ├─ 1_scene02.srcxml
   └─ 1_scene03.srcxml
```

## Advanced Usage

```
noa32c[/nologo] {/p|/x|/c} [/r]
[/pass <password>] [/gp] [/l <list-file>] [/d]
[/raw] [/erisa] [/crypt] [/erisa_crypt] [/time]
[<source-file>] <destination>
```



| Option       | Note                                                         |
| ------------ | ------------------------------------------------------------ |
| /nologo      | no title                                                     |
| /p           | pack (.noa) archive                                          |
| /x           | unpack (.noa) archive                                        |
| /c           | compare (.noa) archive                                       |
| /r           | enable automatic compression                                 |
| /pass        | password for (un)pack                                        |
| /gp          | automatically generates passwords. <br />The generated password can be found in the list file. |
| /l           | specific a list file                                         |
| /d           | pack recursively                                             |
| /raw         | disable compression                                          |
| /erisa       | enable compression                                           |
| /crypt       | encrypt and pack                                             |
| /erisa_crypt | compress, encrypt and pack                                   |
| /time        | measure the time of (up)pack                                 |

## Refenrence

https://forums.fuwanovel.moe/topic/22068-help-regarding-noa-archives/

