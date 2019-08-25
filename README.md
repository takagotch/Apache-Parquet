### apache-parquet
---
https://parquet.apache.org/

```java
mydata = LOAD '/some/path' USING parquet.pig.ParquetLoader();
```

```sh
wget -nv http://archive.apache.org/dist/thrift/0.12.0/thrift-0.12.0.tar.gz
tar xzf thrift-0.12.0.tar.gz
cd thrift-0.12.0
chomd +x ./configure
./configure --disable-gen-erl --disable-gen-hs --without-ruby --without-haskell --without-erlang --without-php --without-nodejs
brew install thrift@0.12
export PATH="/usr/local/opt/thrift@0.12/bin:$PATH"
LC_ALL=C mvn clean install
SET parquet.page.size 1048576 -- default. this is yourmin read/write unit.
```

```
```


