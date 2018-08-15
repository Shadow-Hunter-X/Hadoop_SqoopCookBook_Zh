  无论是在不同的应用程序间移动个人旅游照片还是企业系统将移动字节数据，从多个数据源集成数据依然是十分有挑战性的。
  目前数据存储更易于访问，得益于目前大量广泛使用的存储系统及其配套工具,对于目前那些主流的关系型数据库，于几十年几乎在各工业领域被用于存储大规模数据。
  关系型数据经常用于存储企业有价值的数据，如果条件允许，使用Hadoop进行管理和处理数据，
  实际上hadoop已经成为大数据处理的标准。

  一些成功的关系型数据库供应商将集成Hadoop到他们的产品中，从关系型数据库中导入导出数据是充满挑战和艰辛的。由于传输过程中需要谨慎处理，对于 Apach Sqoop 是 'SQL to Hadoop'的缩写。被创建用来在关系数据库和Hadoop间进行双向数据传输。
  利用 MapReduce的 ， Hadoop的执行引擎 ，sqoop执行传输时，使用并行方式。

  如果你正在阅读本书，那么你之前可能已经对hadoop有所了解，特别是通过 Aaron Kimball 的相关著作，
从以前的了解中，以已经知道在hadoop和数据库中数据传输是进行sqoop的优化操作。但显而易见优化操作时针对高级用户的,一个命令行接口提供60个参数，不仅是功能强大也是让人迷惑的。在本书中，将聚焦于参数的常规应用，以帮助你配置，使用sqoop在你自己的环境中。

<font color=#00ffff>chapter - 1</font> 将带你了解在使用sqoop时的先决条件。你将学习到在hadoop集群的任意节点上下载，安装，配置sqoop.
<font color=#00ffff>chapter - 2,3,4</font> 专注于使用各种示例将数据从数据到如到Hadoop系统中。如果你需要将生成，已加工，备份数据，将数据从Hadoop传输到数据库，那么<font color=#00ffff>chapter - 5</font>

<font color=#00ffff>chapter - 6</font> 将集中在将Hadoop系统和sqoop的集成,我们将演示如何Hadoop中的Oozie任务调度集成;与如何将数据载入到Hadoop数据仓库和HBase数据库中。

对于更高级的操作，sqoop支持依托关系数据库本地特征的特殊连接器。sqoop包括Mysql和PostgreSQL的本地连接器，并且有针对Teradata, Netezza, Couch‐
base, Oracle 的连接器供下载。