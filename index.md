
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

    <title>mysql简介</title>

</head>
<body>
<h1>MySql(关系型数据库管理系统)</h1>
<ol>
    <div>MySQL是一个关系型数据库管理系统，由瑞典MySQL AB 公司开发，目前属于 Oracle 旗下产品。MySQL 是最流行的关系型数据库管理系统之一，在 WEB 应用方面，MySQL是最好的 RDBMS
        (Relational Database Management System，关系数据库管理系统) 应用软件。
    </div>
    <div>MySQL是一种关系数据库管理系统，关系数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，这样就增加了速度并提高了灵活性。</div>
    <div>MySQL所使用的 SQL 语言是用于访问数据库的最常用标准化语言。MySQL 软件采用了双授权政策，分为社区版和商业版，由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，一般中小型网站的开发都选择 MySQL
        作为网站数据库。
    </div>
    <div>由于其社区版的性能卓越，搭配 PHP 和 Apache 可组成良好的开发环境。</div>
</ol>
<br>
<br>
<h2>应用环境</h2>
<ol>

    <div>与其他的大型数据库例如 Oracle、DB2、SQL Server等相比，MySQL 自有它的不足之处，但是这丝毫也没有减少它受欢迎的程度。对于一般的个人使用者和中小型企业来说，MySQL提供的功能已经绰绰有余，而且由于
        MySQL是开放源码软件，因此可以大大降低总体拥有成本。
    </div>

    <div>Linux作为操作系统，Apache 或Nginx作为 Web 服务器，MySQL
        作为数据库，PHP/Perl/Python作为服务器端脚本解释器。由于这四个软件都是免费或开放源码软件（FLOSS)，因此使用这种方式不用花一分钱（除开人工成本）就可以建立起一个稳定、免费的网站系统，被业界称为“LAMP“或“LNMP”组合。
    </div>
    <br>

    <div style="width: 1000px;display:none;word-break: break-all;word-wrap: break-word;">
        ==mahuaBegin==c3fa46cf60542865e8dee78203e62ef56e74365380c8d6c64102af2d40443f5488099fa8786624b28312aa924c2bc431a549252b3fbc09ccdd272299cb2f5777c20fb0c338e7cda144835e30e29d4f94945880c5b9ebd6c969bbb139dc45c5cbb74c65b08f93a989a848c0b11cef49191d66b5c43c72b3e468fd59248cc4a911970800ad01a31222f2af81b04f3b5ebed5035a7aab38cd81eac55e286ade36b35526a7b1ef01cacf629b141b1fcd7df6be501ab868c871319c88961a63513f690b9963caa68dddde806dad1cf6d76c162799ff6318c35ed4dd6488d56be4bd9cb28ffc173f6e709385b806cebf0d9dc3d05bc5e1431c0722e14d564d3418724dfe19ac0b0705d36972d4c362839a67ee4a8a043c4a3a578e9e5cdc984deba4c6052330b5fae332fb48c917705569530339bae13dd71302ce8d2b7d3882f6d3afe8a638db79c25c1e68887fbc2c952ed6a7a6555769ec2ff5ba35dfead5c61f7db663fcd4134180846cccf6f312ea20ca362bc196b8ea95e2719ec5b8439709b89cd6ca4d8f7b4bc68dcb23eac6e5c5ee8894c6b48c5a974275e81b43c371ab52==mahuaEnd==
    </div>
</ol>


<h2>系统特性</h2>
<ol>
    <div>1．使用 C和 C++编写，并使用了多种编译器进行测试，保证了源代码的可移植性。</div>
    <div>2．支持 AIX、FreeBSD、HP-UX、Linux、Mac OS、NovellNetware、OpenBSD、OS/2 Wrap、Solaris、Windows等多种操作系统。</div>
    <div>3．为多种编程语言提供了 API。这些编程语言包括 C、C++、Python、Java、Perl、PHP、Eiffel、Ruby,.NET和 Tcl 等。</div>
    <div>4．支持多线程，充分利用 CPU 资源。</div>
    <div>5．优化的 SQL查询算法，有效地提高查询速度。</div>
    <div>6．既能够作为一个单独的应用程序应用在客户端服务器网络环境中，也能够作为一个库而嵌入到其他的软件中。</div>
    <div>7．提供多语言支持，常见的编码如中文的 GB 2312、BIG5，日文的 Shift_JIS等都可以用作数据表名和数据列名。</div>
    <div>8．提供 TCP/IP、ODBC 和 JDBC等多种数据库连接途径。</div>
    <div>9．提供用于管理、检查、优化数据库操作的管理工具。</div>
    <div>10．支持大型的数据库。可以处理拥有上千万条记录的大型数据库。</div>
    <div>11．支持多种存储引擎。</div>
    <div>12.MySQL 是开源的，所以你不需要支付额外的费用。</div>
    <div>13.MySQL 使用标准的 SQL数据语言形式。</div>
    <div>14.MySQL 对 PHP 有很好的支持，PHP是比较流行的 Web 开发语言。</div>
    <div>15.MySQL是可以定制的，采用了 GPL协议，你可以修改源码来开发自己的 MySQL 系统。</div>
    <div>16.在线 DDL/更改功能，数据架构支持动态应用程序和开发人员灵活性（5.6新增）</div>
    <div>17.复制全局事务标识，可支持自我修复式集群（5.6新增）</div>
    <div>18.复制无崩溃从机，可提高可用性（5.6新增）</div>
    <div>19.复制多线程从机，可提高性能（5.6新增）</div>
    <div>20.3倍更快的性能（5.7 新增）</div>
    <div>21.新的优化器（5.7新增）</div>
    <div>22.原生JSON支持（5.7新增）</div>
    <div>23.多源复制（5.7新增）</div>
    <div>24.GIS的空间扩展 （5.7新增）</div>
</ol>


</body>
</html>
