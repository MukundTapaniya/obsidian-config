---
date: 2024-12-10T17:20
tags:
  - mutaOS
  - archiso
  - core_config
---
---
hostname : mutaOS
password : [no password]

username : mukund
password : mukund

---
passwd [[file]]
```
root:x:0:0:root:/root:/usr/bin/bash
mukund:x:1000:1000::/home/mukund:/usr/bin/fish
```
---
create password with
```
openssl passwd -6
```
---
shadow [[file]] 
```
root:x:0:0:root:/root:/usr/bin/bash
mukund:x:1000:1000:$6$rOj4gyf6i2VwaW81$mwvL3M7Y2pc9cUNlMzQW2ic2zMxAXuNUVdyPxqFaH2dCX5/dvstyT3BnTo6qNfcJyGv8gAtk2CSKqwdawhFEt1:/home/mukund:/usr/bin/fish
```
---
gshadow [[file]]
```
root:!*::root
mukund:!*::
```
---

