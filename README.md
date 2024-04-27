# OpenSSL-Linux-Build

***Building latest OpenSSL on Linux***

```
wget https://www.openssl.org/source/openssl-3.3.0.tar.gz
tar -zxf openssl-3.3.0.tar.gz
rm openssl-3.3.0.tar.gz
cd openssl-3.3.0
./Configure
make
make install
ldconfig /usr/local/lib64/
```
