[![version](https://badge.fury.io/gh/aliyun%2Faliyun-emapreduce-sdk.svg)](https://badge.fury.io/gh/aliyun%2Faliyun-emapreduce-sdk)
[![build](https://api.travis-ci.org/aliyun/aliyun-emapreduce-datasources.svg?branch=master-2.x)](https://travis-ci.org/aliyun/aliyun-emapreduce-datasources)
[![HitCount](http://hits.dwyl.io/aliyun/aliyun-emapreduce-sdk.svg)](http://hits.dwyl.io/aliyun/aliyun-emapreduce-sdk)
[![License Apache2](https://img.shields.io/badge/license-Apache2-blue.svg?style=flat-square)](https://github.com/aliyun/aliyun-emapreduce-sdk/blob/master-2.x/LICENSE)

# E-MapReduce DataSources

## Requirements

- Spark 1.3+

## Introduction

- This project supports interaction with Aliyun's base service, e.g. OSS, ODPS, LogService and ONS, in Spark runtime environment.

## Build and Install

```

	    git clone https://github.com/aliyun/aliyun-emapreduce-datasources.git
	    cd  aliyun-emapreduce-datasources
	    mvn clean package -DskipTests

```

#### Use SDK in Eclipse project directly

- copy sdk jar to your project
- right click Eclipse project -> Properties -> Java Build Path -> Add JARs
- choose and import the sdk
- you can use the sdk in your Eclipse project

#### Maven 

```
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-maxcompute_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>

        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-logservice_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>

        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-tablestore</artifactId>
            <version>2.1.0</version>
        </dependency>

        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-ons_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>

        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-mns_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-redis_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-hbase_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-jdbc_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-dts_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-kudu_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>

        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-datahub_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>

        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-druid_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-sql_2.11</artifactId>
            <version>2.1.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-oss</artifactId>
            <version>2.0.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-common</artifactId>
            <version>2.1.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.aliyun.emr</groupId>
            <artifactId>emr-kafka-client-metrics</artifactId>
            <version>2.1.0</version>
        </dependency>

```

## Run tests

* [How to run tests](docs/how_to_run_tests.md)

## JindoFS/OSS support

* [Hadoop on JindoFS/OSS](docs/jindofs_sdk_how_to.md) (Hive, Spark, Presto, Impala, Hbase and Flink are also supported)

## MaxCompute support

* [Spark on MaxCompute](docs/aliyun_odps_support.md)

## ONS support

* [Spark on ONS](docs/aliyun_ons_support.md)

## LogService support

* [Spark on LogService](docs/aliyun_logservice_support.md)

## TableStore support

* [HadoopMR on TableStore](docs/HadoopMR-on-TableStore.md)
* [Spark on TableStore](docs/Spark-on-TableStore.md)
* [Hive/SparkSQL on TableStore](docs/Hive-SparkSQL-on-TableStore.md)

## License

Licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)
