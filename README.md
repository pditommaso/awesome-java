Awesome Java
================

A curated list of awesome Java libraries inspired by other Awesome lists

AOT compilers 
-------------
* [Excelsior JET](https://www.excelsiorjet.com/) 
* [Excelsior JET Gradle plugin](https://github.com/excelsior-oss/excelsior-jet-gradle-plugin) 
* [GraalVM AOT compiler](http://www.oracle.com/technetwork/oracle-labs/program-languages/overview/index.html) 

Annotation processor
--------------------
* [immutables](https://github.com/immutables/immutables) - Annotation processor to create immutable objects and builders.
* [Lombok](https://projectlombok.org/) - Lombok is used to reduce boilerplate code for model/data objects.
* [mapstruct](https://github.com/mapstruct/mapstruct) - An annotation processor for generating type-safe bean mappers

Big collections, cache & off-heap memory  
----------------------------------------

* [Caffeine](https://github.com/ben-manes/caffeine) - High performance caching library for Java 8.
* [Cache2k](https://github.com/cache2k/cache2k) - Lightweight, high performance Java caching.
* [Capsule](https://github.com/usethesource/capsule) - Capsule Hash Trie Collections Library.
* [Cqengine](https://github.com/npgall/cqengine) - NoSQL collection indexing and query engine with ultra-low latency.
* [Coherence](https://github.com/oracle/coherence) - Oracle Coherence [Community Edition](https://coherence.community/) and [Hibernate support](http://coherence.java.net/coherence-hibernate/1.0.0/).
* [ConcurrentLinkedHashMap](https://github.com/ben-manes/concurrentlinkedhashmap) - ConcurrentLinkedHashMap for Java.
* [Concurrent-trees](https://github.com/npgall/concurrent-trees) - Concurrent Radix Trees and Concurrent Suffix Trees for Java.
* [Chronicle-Map](https://github.com/OpenHFT/Chronicle-Map) - High performance key-value store.
* [Java-concurrent-hash-trie-map](https://github.com/romix/java-concurrent-hash-trie-map) - Concurrent trie hash map implementation.
* [LArray](https://github.com/xerial/larray) - Large off-heap arrays and memory-mapped file (mmap).
* [Level-db](https://github.com/dain/leveldb) - Port of LevelDB to Java.
* [Lmdb-jni](https://github.com/chirino/lmdbjni) - Lightning Memory-Mapped Database.
* [LMAXCollections](https://github.com/LMAX-Exchange/LMAXCollections) - LMAX Collections.
* [PalDB](https://github.com/linkedin/PalDB) - An embeddable write-once key-value store.
* [Radix-tree](https://github.com/thegedge/radix-tree) - Radix tree data structure that adheres to the `java.util.Map` interface.
* [Mapdb](https://github.com/jankotek/mapdb) - Concurrent Maps, Sets and Queues backed by disk storage or off-heap-memory.
* [Vmlens](https://github.com/vmlens/executor-service) - ExecutorService supporting multiple writing and a single reading thread.
* [Weak-lock-free](https://github.com/raphw/weak-lock-free) - concurrent map with weak keys and a detached thread local storage.

Messaging & queues 
------------------
* https://github.com/real-logic/agrona
* https://github.com/JCTools/JCTools
* https://github.com/apache/ratis
* https://github.com/softwaremill/jox - Fast and Scalable Channels in Java

Checkpoint & restore 
--------------------
* https://github.com/openjdk/crac
* https://wiki.openjdk.java.net/display/crac/Main
* https://openjdk.java.net/projects/crac/
* https://foojay.io/today/introducing-the-openjdk-coordinated-restore-at-checkpoint-project/
* https://thenewstack.io/azul-proposes-java-state-api-to-speed-app-start-up-times/
* https://mbien.dev/blog/entry/crac-coordinated-restore-at-checkpoint
* https://danheidinga.github.io/Everyone_wants_fast_startup/
* https://github.com/HanSolo/crac4

CLI parser 
----------
* [Airline](https://github.com/airlift/airline) - Annotation-based framework for parsing Git like command line structures.
* [args4j](https://github.com/kohsuke/args4j)
* [barclay](https://github.com/broadinstitute/barclay) - Command line argument parser and online documentation generation utilities.
* [cli-toolbelt](https://github.com/simplifyops/cli-toolbelt) - Annotation based command line builder with support for git-like subcommands, basic argument parsing and works with others like JewelCLI.
* [CmdOption](https://github.com/ToToTec/CmdOption) - Simple annotation-driven command line parser.
* [commandline](https://github.com/jankroken/commandline) - Annotation based command line parser.
* [jbock](https://github.com/h908714124/jbock) - Curiously simple CLI parser.
* [JewelCLI](https://github.com/lexicalscope/jewelcli/) - Annotated interface to automatically parse and present command line arguments.
* [jopt-simple](https://github.com/jopt-simple/jopt-simple) - Java library for parsing command line options.
* [picocli](http://picocli.info) - Annotation based command line parser with strong typing and support for git-like subcommands.

Crypto 
------- 
* [java-otp](https://github.com/jchambers/java-otp/) - A one-time password (HOTP/TOTP) library for Java.
* [OTP-Java](https://github.com/BastiaanJansen/OTP-Java) - One-time password generator library according to RFC 4226 (HOTP) and RFC 6238 (TOTP).
* [two-factor-auth](https://github.com/j256/two-factor-auth) - Two Factor Authentication Java code implementing the Time-based One-time Password Algorithm.
* [JWT-Java](https://github.com/BastiaanJansen/JWT-Java) - JSON Web Token implementation for Java according to RFC 7519.

DB engines
----------
* [Derby](https://db.apache.org/derby/) - Open source relational database implemented entirely in Java.
* [Gaffer](https://github.com/gchq/Gaffer) - Large-scale entity and relation database supporting aggregation of properties.
* [H2](https://github.com/h2database/h2database) - H2 is an embeddable RDBMS written in Java.
* [HSQLDB](https://sourceforge.net/p/hsqldb/hsqldb/ref/master) - HSQLDB (Hyper SQL Database) is a relational database management system written in Java, offering a fast, small database engine which offers both in-memory and disk-based tables
* [LevelDB](https://github.com/dain/leveldb) - Port of LevelDB to Java.
* [PalDB](https://github.com/linkedin/PalDB) - Embeddable write-once key-value store written in Java.
* [MapDB](https://github.com/jankotek/mapdb/) - Fast and easy to use embedded Java database engine.
* [Xodus](https://github.com/JetBrains/xodus/) - JetBrains Xodus is a Java transactional schema-less embedded database.

Dataflow & parallelization
------------------------
* [Actr](https://github.com/zakgof/actr) - Simple, fast and typesafe Java actor model implementation.
* [JCSP](https://github.com/CSPforJAVA/jcsp) - Communicating Sequential Processes (CSP) for Java.
* [Quasar](https://github.com/puniverse/quasar) - Fibers, Channels and Actors for the JVM.
* [GPars](https://github.com/GPars/GPars) - Concurrency and parallelism framework for the JVM.
* [Pipes](https://github.com/tinkerpop/pipes) - Lazy Data Flow Framework.
* [Pekka](https://pekko.apache.org/) - Apache Pekko is a fork of Akka 2.6.x.

DI
-----
* [Dagger](https://github.com/google/dagger) - Fast dependency injector.
* [Tiger](https://github.com/google/tiger) - Fastest java dependency injection framework.
* [Purejin](https://github.com/jbee/purejin) - Java dependency injection through code.

Error handling
--------------
* [Failsafe](https://github.com/jhalterman/failsafe) - Simple, sophisticated failure handling.
* [Resilience4j](https://github.com/resilience4j/resilience4j) - Fault tolerance library designed for Java8 and functional programming.

File system 
-------------
* [Amazon-S3-FileSystem-NIO2](https://github.com/Upplication/Amazon-S3-FileSystem-NIO2) - S3 File System Provider for Java 7.
* [Azure-storage-blob-nio](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/storage/azure-storage-blob-nio) - NIO File system for Azure storage.
* [java-storage-nio](https://github.com/googleapis/java-storage-nio) - NIO File system for Google storage.
* [Fuse-jna](https://github.com/EtiennePerot/fuse-jna) - Java bindings to FUSE using JNA.
* [Javafs](https://github.com/puniverse/javafs) - Java filesystems as FUSE (++).
* [Jimfs](https://github.com/google/jimfs) - in-memory file system for Java 7+.
* [Jsr203-hadoop](https://github.com/damiencarol/jsr203-hadoop) - Java NIO file system provider for HDFS.
* [Nfs4j](https://github.com/dCache/nfs4j) - Pure Java NFSv3 and NFSv4.1 implementation.
* [s3fs-nio](https://github.com/carlspring/s3fs-nio/) - Java (NIO2) FileSystem Provider for Amazon AWS S3.
* [Tachyon](https://github.com/amplab/tachyon) - Memory Centric Reliable Distributed Storage.

Hashing 
----------
* [Lz4-java](https://github.com/jpountz/lz4-java) - LZ4 compression for Java.
* [xxHash](https://github.com/Cyan4973/xxHash) - Extremely fast non-cryptographic hash algorithm.
* [Zero-Allocation-Hashing](https://github.com/OpenHFT/Zero-Allocation-Hashing) - Zero-allocation hashing for Java.
* [hashids-java](https://github.com/10cella/hashids-java) - generate short unique ids from integers - https://hashids.org/java/
* [icecore-hashids](https://github.com/arcticicestudio/icecore-hashids) - lightweight generator for short, unique, non-sequential and decodable Hashids from non-negative numbers
* [jnanoid](https://github.com/aventrix/jnanoid) - tiny (108 bytes), secure, URL-friendly, unique string ID generator - https://github.com/ai/nanoid
* [friendly-id](https://github.com/Devskiller/friendly-id) - Converts a given UUID to Base62 format (22 chars)
* [hash4j](https://github.com/dynatrace-oss/hash4j) - Dynatrace hash library for Java

Http 
-----
* [Http-builder-ng](https://github.com/dwclark/http-builder-ng) - The Easy Http Client for Groovy.
* [OkHttp](https://github.com/square/okhttp) - HTTP+SPDY client for Android and Java applications.
* [Unirest](http://unirest.io/java.html) - Lightweight HTTP libraries for Java.
* [retrofit](https://github.com/square/retrofit) - Type-safe HTTP client for Android and Java.

Logging
-------
* [blitz4j](https://github.com/Netflix/blitz4j) - Logging framework for fast asynchronous logging.
* [log4j2](https://logging.apache.org/log4j/2.x/) - Async Loggers have 18 times higher throughput than Log4j 1.x and Logback.

Math & ML
---------
* [Jblas](https://github.com/mikiobraun/jblas) - Linear Algebra for Java.
* [FastR](https://github.com/allr/purdue-fastr) - R language intepreter.  
* [Renjin](https://github.com/bedatadriven/renjin) - JVM-based interpreter for the R language.
* [Tribuo](https://github.com/oracle/tribuo) - Machine learning lib by Oracle

Messaging 
----------
* [Aeron](https://github.com/real-logic/Aeron) - Efficient reliable unicast and multicast message transport.
* [MBassador](https://github.com/bennidi/mbassador) - Event bus aiming at ease of use and performance.
* [Mappedbus](https://github.com/caplogic/Mappedbus) - Library for low latency IPC between multiple Java processes/JVMs.

Native invocation / FFI 
------------------------
* [JavaCpp](https://github.com/bytedeco/javacpp) - Bridge between Java and native C++.
* [JNA](https://github.com/java-native-access/jna) - Java Native Access.

Packaging
--------- 
* [badass-runtime-plugin](https://github.com/beryx/badass-runtime-plugin) - Create a custom runtime image of your non-modular application
* [pf4j](https://github.com/pf4j/pf4j) - Plugin Framework for Java

Regular expressions
--------------------
* [RE2/J](https://github.com/google/re2j) - Linear time regular expression matching in Java.

Reactive stream
-----------------
* [JDeferred](https://github.com/jdeferred/jdeferred) - Java Deferred/Promise library similar to JQuery.
* [Reactive-streams](https://github.com/reactive-streams/reactive-streams-io/) - Reactive Streams Network Protocol.
* [Simple-react](https://github.com/aol/simple-react) - Future Streams & Async Data Structures for Java 8.

Serialization
---------------
* [Blixtser](https://github.com/Mojang/blixtser) - Fast Serialization library.
* [Fast-serialization](https://github.com/RuedigerMoeller/fast-serialization) - Fast java serialization drop in-replacement.
* [Ion](https://github.com/amznlabs/ion-java) - Java streaming parser/serializer for Ion.
* [json-tree](https://github.com/dhis2/json-tree) - A lazily parsed JSON virtual tree library.
* [Kryo](https://github.com/EsotericSoftware/kryo) - Fast, efficient, automatic Java serialization and cloning.
* [Kryo-serializers](https://github.com/magro/kryo-serializers)
* [Java-Deserialization-Cheat-Sheet](https://github.com/GrrrDog/Java-Deserialization-Cheat-Sheet)
* [Message-pack](https://github.com/msgpack/msgpack-java) - MessagePack serializer implementation for Java

Syntax parsing
--------------
* [In-memory-antlr](https://github.com/julianthome/inmemantlr) - In Memory compilation of ANTLR grammars
* [Java-parser](https://github.com/javaparser/javaparser) - Java 9 Parser and Abstract Syntax Tree for Java
* [Groovy-Parrot](https://github.com/danielsun1106/groovy-parser) - Brand new parser for Groovy programming language.
* [Rewrite](https://github.com/openrewrite/rewrite) - Semantic code search and transformation via Java AST transformation.

Templating 
----------
* [handlebars](https://github.com/jknack/handlebars.java) - Logic-less and semantic Mustache templates with Java

Task scheduler
--------------
* [db-scheduler](https://github.com/kagkarlsson/db-scheduler) - Persistent cluster-friendly scheduler for Java
* [Jobrunr](https://github.com/jobrunr/jobrunr) - Background processing in Java. Backed by persistent storage.
* [Workhorse](https://github.com/coodoo-io/workhorse) - Java EE Job Engine for background jobs and business critical tasks
* [Sundial](https://github.com/knowm/Sundial) - Lightweight Java job scheduling framework forked from Quartz
* [ShedLock](https://github.com/lukas-krecan/ShedLock) - Distributed lock for your scheduled tasks

Testing
---------
* [βetamax](https://github.com/betamaxteam/betamax) - Tool for mocking external HTTP web services and REST APIs.
* [Ersatz](http://stehno.com/ersatz/) - Mock HTTP server for testing client code.
* [Overcast](https://github.com/xebialabs/overcast) - Helper classes to write your tests against hosts in the cloud.
* [Spock](https://github.com/spockframework/spock) - Enterprise-ready testing and specification framework.
* [WireMock](https://github.com/tomakehurst/wiremock) - A tool for mocking HTTP services.

Other 
------
* [asciitable](https://github.com/vdmeer/asciitable) - Several implementations of a text table, originally using ASCII and UTF-8 characters for borders.
* [Allocation instrumenter](https://github.com/google/allocation-instrumenter) - Java agent that rewrites bytecode to instrument allocation sites.
* [Arthas](https://github.com/alibaba/arthas) - Alibaba Java Profiling and Diagnostic Tool Arthas.
* [Bloofi](https://github.com/lemire/bloofi) - Multidimensional Bloom filters.
* [Cfg4j](https://github.com/cfg4j/cfg4j) - Modern configuration library for distributed apps.
* [directory-watcher](https://github.com/gmethvin/directory-watcher) - cross-platform Java recursive directory watcher, with a JNA macOS watcher.
* [Docker-java](https://github.com/docker-java/docker-java) - Java Docker API Client.
* [Drip](https://github.com/ninjudd/drip) - Fast JVM launching without the hassle of persistent JVMs.
* [emoji-java](https://github.com/Coding/emoji-java) - Java library that helps you use Emojis in your java applications.
* [Fastfilter](https://github.com/FastFilter/fastfilter_java) - Fast Approximate Membership (Bloom) Filters (aka [xor-filter](https://github.com/FastFilter/xorfilter)) 
* [fast-classpath-scanner](https://github.com/lukehutch/fast-classpath-scanner) - Uber-fast, ultra-lightweight Java classpath scanner.
* [file-leak-detector](https://github.com/kohsuke/file-leak-detector) - Java agent that detects file handle leak.
* [Goodtimes](https://github.com/bdkosher/goodtimes) - Java 8 Date/Time API enhancements for Groovy.
* [java-string-similarity](https://github.com/tdebatty/java-string-similarity)- Various string similarity and distance algorithms.
* [jOOR](https://github.com/jOOQ/jOOR) - Fluent Reflection in Java.
* [jvmtop](https://github.com/patric-r/jvmtop/) - Java monitoring for the command-line - Java 11 fork [see here](https://github.com/patric-r/jvmtop/issues/109#issuecomment-622044148)
* [jmail](https://github.com/RohanNagar/jmail) - modern and lightweight library for working with email addresses in Java
* [K8s-cli-java](https://github.com/codementor/k8s-cli-java) - Simple Java Demo of Kubernetes kubectl plugin + Java Graal native image.
* [fabric8io/kubernetes-client](https://github.com/fabric8io/kubernetes-client) - Java client for Kubernetes & OpenShift.
* [MmgGameApiJava](https://github.com/vbrusca/MmgGameApiJava) - Java library for creating 2D games right in the IDE.
* [Packrat](https://github.com/jhspetersson/packrat) - Gatherers library for Java Stream API
* [Permit-reflect](https://github.com/nqzero/permit-reflect) - Permit reflective access for java 11.
* [square/OKIO](https://github.com/square/OKIO) - A modern I/O API for Java.
* [text-io](https://github.com/beryx/text-io) - library for creating interactive console applications in Java
* [TornadoVM](https://github.com/beehive-lab/TornadoVM) - Automatically run Java programs on GPUs
* [RelProxy](https://github.com/jmarranz/relproxy/) - Java and Groovy hot class reloader and Java based shell and scripting.
* [hibernate-types](https://github.com/vladmihalcea/hibernate-types) - Extra types that are not supported by the Hibernate ORM core.
* [java-stream-batch-processing](https://www.baeldung.com/java-stream-batch-processing)
* [Simple-java-mail](https://github.com/bbottema/simple-java-mail) - Simple API, Complex Emails (Jakarta Mail smtp wrapper

Web frameworks 
--------------
* [Jooby](https://github.com/jooby-project/jooby) - Scalable, fast and modular micro web framework for Java.
* [Micronaut](https://github.com/micronaut-projects/micronaut-core) - Micronaut Application Framework.
* [Play framework](https://github.com/playframework/playframework) - High Velocity Web Framework.
* [Ratpack](https://github.com/ratpack/ratpack) - A toolkit for JVM web applications .
* [Spark](https://github.com/perwendel/spark) - A Sinatra inspired framework for java.
* [Vert.x](https://github.com/eclipse/vert.x/) - Vert.x is a tool-kit for building reactive applications on the JVM.

Tutorial
--------
* [Understanding Gradle](https://www.youtube.com/watch?v=Ajs8pTbg8as&list=PLWQK2ZdV4Yl2k2OmC_gsjDpdIBTN0qqkE&index=1)

