elasticsearch-image-1.7.5
=========================================
See https://github.com/kzwang/elasticsearch-image , this version support for elasticsearch 1.7.5

To build a `SNAPSHOT` version, you need to build it with Maven:

```bash
mvn clean package -DskipTest
bin/plugin --install image \
       --url file:target/releases/elasticsearch-image-X.X.X-SNAPSHOT.zip
