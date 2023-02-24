# OpenSSL-Linux-Build

***Building latest OpenSSL on Linux***

```
wget https://www.openssl.org/source/openssl-3.0.8.tar.gz
tar -zxf openssl-3.0.8.tar.gz
rm openssl-3.0.8.tar.gz
cd openssl-3.0.8
./Configure
make
make install
ldconfig /usr/local/lib64/
```
