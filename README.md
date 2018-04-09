cifaz.gitlab-zh
=====================
[![Build Status](https://travis-ci.org/andrewrothstein/gitlab-zh.svg?branch=master)](https://travis-ci.org/andrewrothstein/gitlab-zh)

## gitlab汉化

### 原始gitlab安装
```
  注安装时尽量不要完全安装新版本, 汉化版本可能没有100%跟上, 尽量低一点, 或查看汉化版后再指定版本安装[gitlab官方链接](https://gitlab.com/xhang/gitlab)
  ansible-galaxy install geerlingguy.gitlab

```

### 汉化安装
``` 
- hosts: local
  become: yes
  roles:
    - gitlab-zh
    
  下载时因为是全量下载可能有点慢, 看网速了
  
```

License
-------

MIT

Author Information
------------------

ccz <hanlin2531@163.com>