# LNIUXTEST.sh

## 运行（不含UnixBench）
```
wget https://raw.githubusercontent.com/chiakge/Linux-Server-Bench-Test/master/linuxtest.sh -N --no-check-certificate && bash linuxtest.sh
```
## 运行（含UnixBench）
```
wget https://raw.githubusercontent.com/chiakge/Linux-Server-Bench-Test/master/linuxtest.sh -N --no-check-certificate && bash linuxtest.sh a
```
运行说明
#不含UnixBench的测试，无网页分享
bash linuxtest.sh

#不含UnixBench的测试，带网页分享
bash linuxtest.sh s

#含UnixBench的测试，不带网页分享
bash linuxtest.sh a

#含UnixBench的测试，带网页分享
bash linuxtest.sh as

#网页分享不包含任何VPSip信息
