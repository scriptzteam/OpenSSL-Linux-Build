# Snowflake-Linux-Build

***Building latest OpenSSL on Linux***

```
wget https://github.com/openssl/openssl/archive/refs/tags/openssl-3.0.7.tar.gz
tar -zxf openssl-3.0.7.tar.gz
rm openssl-3.0.7.tar.gz
cd openssl-3.0.7
./Configure
make
make test
make install
```
