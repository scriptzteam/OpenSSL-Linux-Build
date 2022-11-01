# Snowflake-Linux-Build

***Building latest OpenSSL on Linux***

```
wget https://www.openssl.org/source/openssl-3.0.7.tar.gz
tar -zxf openssl-3.0.7.tar.gz
rm openssl-3.0.7.tar.gz
cd openssl-3.0.7
./Configure
make
make install
```
