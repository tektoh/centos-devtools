centos-devtools Cookbook
=================
各種開発ツールをインストールします。

- Development Tools
- bind-utils
- curl
- elinks
- ethtool
- expect
- iputils
- jwhois
- ltrace
- lynx
- nc
- nmap
- strace
- tcpdump
- telnet
- traceroute
- vim-enhanced
- wget
- zsh

Requirements
------------
CentOS 6

Attributes
----------
* `devtools['packages']`
    - Development Tools 以外でインストールするパッケージ名を配列で指定します。

Usage
-----
```json
{
  "name":"my_node",
  "run_list": [
    "recipe[centos-devtools]"
  ]
}
```
