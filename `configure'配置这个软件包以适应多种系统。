`configure'配置这个软件包以适应多种系统。

用法：./configure [OPTION] ... [VAR = VALUE] ...

要分配环境变量（例如，CC，CFLAGS ...），请将它们指定为
VAR = VALUE。请参阅下面的一些有用变量的描述。

选项的默认值在括号中指定。

组态：
  -h，--help显示此帮助并退出
      --help =特定于此包的短显示选项
      --help =递归显示所有包含的软件包的简短帮助
  -V，--version显示版本信息并退出
  -q，--quiet，--silent不打印`检查...'消息
      --cache-file = FILE在FILE中缓存测试结果[disabled]
  -C， - `--cache-file = config.cache'的--config-cache别名
  -n，--no-create不创建输出文件
      --srcdir = DIR在DIR中找到源文件[configure dir or`..']

安装目录：
  --prefix = PREFIX在PREFIX中安装与体系结构无关的文件
                          [/ USR /本地]
  --exec-prefix = EPREFIX在EPREFIX中安装与体系结构相关的文件
                          [字首]

默认情况下，`make install'将安装所有文件
`/ usr / local / bin'，`/ usr / local / lib'等。你可以指定
一个使用`--prefix'的`/ usr / local'以外的安装前缀，
例如`--prefix = $ HOME'。

为了更好地控制，请使用下面的选项。

微调安装目录：
  --bindir = DIR用户可执行文件[EPREFIX / bin]
  --sbindir = DIR系统管理员可执行文件[EPREFIX / sbin]
  --libexecdir = DIR程序可执行文件[EPREFIX / libexec]
  --sysconfdir = DIR只读的单机数据[PREFIX / etc]
  --sharedstatedir = DIR可修改的独立于体系结构的数据[PREFIX / com]
  --localstatedir = DIR可修改的单机数据[PREFIX / var]
  --libdir = DIR目标代码库[EPREFIX / lib]
  --includedir = DIR C头文件[PREFIX / include]
  --oldincludedir =非gcc的DIR C头文件[/ usr / include]
  --datarootdir = DIR只读arch.--独立数据根[PREFIX / share]
  --datadir = DIR只读架构独立数据[DATAROOTDIR]
  --infodir = DIR信息文档[DATAROOTDIR / info]
  --localedir = DIR语言环境相关数据[DATAROOTDIR /语言环境]
  --mandir = DIR man文档[DATAROOTDIR / man]
  --docdir = DIR文档根目录[DATAROOTDIR / doc / PACKAGE]
  --htmldir = DIR html文档[DOCDIR]
  --dvidir = DIR dvi文档[DOCDIR]
  --pdfdir = DIR pdf文档[DOCDIR]
  --psdir = DIR ps文档[DOCDIR]

系统类型：
  --build = BUILD配置在BUILD上构建[猜测]
  --host = HOST交叉编译构建程序在HOST [BUILD]上运行
  --target = TARGET配置用于为TARGET构建编译器[HOST]

可选功能和软件包：
   --disable-option-checking忽略无法识别的--enable / - 带有选项
   --disable-FEATURE不包含FEATURE（与--enable-FEATURE = no相同）
   --enable-FEATURE [= ARG]包括FEATURE [ARG = yes]
   --with-PACKAGE [= ARG]使用PACKAGE [ARG = yes]
   --with-PACKAGE不使用PACKAGE（与--with-PACKAGE = no相同）
   --with-libdir = NAME在... / NAME中查找库，而不是在/ lib中查找库
   --disable-rpath禁用传递附加运行时库
                           搜索路径
   --enable-re2c-cgoto启用-g标志以re2c使用计算的goto gcc扩展名
  --disable-GCC-全球的REG
                           是否启用GCC全局寄存器变量

SAPI模块：

  --with-apxs2 = FILE构建共享的Apache 2.0 Handler模​​块。 FILE是可选的
                          Apache apxs工具apxs的路径名
  --disable-cli禁用构建PHP的PHP版本
                          （这迫使 - 无梨）
  --enable-embed = TYPE实验：启用嵌入式SAPI库的构建
                          TYPE是'共享'或'静态'。 TYPE =共享
  --enable-fpm启用fpm SAPI可执行文件的构建
  --with-fpm-user = USER设置用户为php-fpm运行。 （默认：无人）
  --with-fpm-group = GRP将php-fpm设置为运行。对于系统用户来说，这个
                          通常应设置为匹配fpm用户名（默认值：无）
  --with-fpm-systemd激活系统集成
  --with-fpm-acl使用POSIX访问控制列表
  --with-litespeed将PHP构建为litespeed模块
  --enable-phpdbg生成phpdbg
  --enable-phpdbg-webhelper构建phpdbg web SAPI支持
  --enable-phpdbg-debug在调试模式下生成phpdbg
  --disable-cgi禁用PHP的构建CGI版本

常规设置：

   --enable-gcov启用GCOV代码覆盖（需要LTP） - 仅供开发人员使用！
   --enable-debug编译调试符号
   --with-layout = TYPE设置如何安装文件。 类型可以
                           可以是PHP或GNU [PHP]
  --with-配置文件中路径= PATH
                           设置寻找php.ini的路径[PREFIX / lib]
  --with-配置文件中扫描-DIR= PATH
                           设置扫描配置文件的路径
   --enable-sigchild启用PHP自己的SIGCHLD处理程序
   --enable-libgcc启用与libgcc的显式链接
   --disable-short-tags禁用短格式<？ 开始标记默认情况下
   --enable-dmalloc启用dmalloc
   --disable-ipv6禁用IPv6支持
   --enable-dtrace启用DTrace支持
   --enable-fd-setsize设置描述符集的大小

扩展：

  --with-EXTENSION =共享[，PATH]

    注意：并非所有扩展都可以构建为“共享”。

    例如：--with-foobar = shared，/ usr / local / foobar /

      o将foobar扩展程序构建为共享扩展程序。
      o foobar包的安装前缀是/ usr / local / foobar /


  --disable-all禁用默认启用的所有扩展

  --disable-libxml禁用LIBXML支持
  --with-libxml-dir = DIR LIBXML：libxml2安装前缀
  --with-openssl = DIR包含OpenSSL支持（需要OpenSSL> = 1.0.1）
  --with-kerberos = DIR OPENSSL：包含Kerberos支持
  --with-system-ciphers OPENSSL：使用系统默认密码列表，而不是硬编码值
  --with-pcre-regex = DIR包括Perl兼容的正则表达式支持。
                          DIR是PCRE安装前缀BUNDLED
  --with-pcre-jit启用PCRE JIT功能（仅限BUNDLED）
  --with-PCRE-的valgrind = DIR
                          启用PCRE valgrind支持。仅限开发者！
  --without-sqlite3 = DIR不包含SQLite3支持。 DIR是前缀
                          SQLite3安装目录。
  --with-zlib = DIR包含ZLIB支持（需要zlib> = 1.0.9）
  --with-zlib-dir = <DIR>定义zlib安装目录的位置
  --enable-bcmath启用bc样式精度数学函数
  --with-bz2 = DIR包含BZip2支持
  --enable-calendar启用对日历转换的支持
  --disable-ctype禁用ctype函数
  --with-curl = DIR包含cURL支持
  --enable-dba使用捆绑的模块构建DBA。构建共享DBA
                          扩展名使用--enable-dba = shared
--with-qdbm = DIR DBA：QDBM支持
  --with-gdbm = DIR DBA：GDBM支持
  --with-ndbm = DIR DBA：NDBM支持
  --with-db4 = DIR DBA：Oracle Berkeley DB 4.x或5.x支持
  --with-db3 = DIR DBA：Oracle Berkeley DB 3.x支持
  --with-db2 = DIR DBA：Oracle Berkeley DB 2.x支持
  --with-db1 = DIR DBA：Oracle Berkeley DB 1.x支持/仿真
  --with-dbm = DIR DBA：DBM支持
  --with-tcadb = DIR DBA：东京内阁摘要数据库支持
  --with-lmdb = DIR DBA：闪存映射数据库支持
  --without-cdb = DIR DBA：CDB支持（捆绑）
   - 不可使用的DBA：INI支持（捆绑）
  --disable-flatfile DBA：FlatFile支持（捆绑）
  --disable-dom禁用DOM支持
  --with-libxml-dir = DIR DOM：libxml2安装前缀
  --with-enchant = DIR包含附魔支持。
                          GNU Aspell版本1.1.3或更高版本。
  --enable-exif启用EXIF（来自图像的元数据）支持
  --disable-fileinfo禁用fileinfo支持
  --disable-filter禁用输入过滤器支持
  --with-pcre-dir FILTER：pcre安装前缀
  --enable-ftp启用FTP支持
  --with-openssl-dir = DIR FTP：openssl安装前缀
  --with-gd = DIR包含GD支持。 DIR是GD库的基础
                          安装目录BUNDLED
  --with-webp-dir = DIR GD：将路径设置为libwebp安装前缀
  --with-jpeg-dir = DIR GD：将路径设置为libjpeg安装前缀
  --with-png-dir = DIR GD：将路径设置为libpng安装前缀
  --with-zlib-dir = DIR GD：设置libz安装前缀的路径
  --with-xpm-dir = DIR GD：将路径设置为libXpm安装前缀
  --with-freetype-dir = DIR GD：将路径设置为FreeType 2安装前缀
  --enable-gd-jis-conv GD：启用JIS映射的日文字体支持
  --with-gettext = DIR包含GNU gettext支持
  --with-gmp = DIR包含GNU MP支持
  --with-mhash = DIR包含mhash支持
  --disable-hash禁用散列支持
  --without-iconv = DIR排除iconv支持
  --with-imap = DIR包含IMAP支持。 DIR是c-client安装前缀
  --with-kerberos = DIR IMAP：包含Kerberos支持。 DIR是Kerberos安装前缀
  --with-imap-ssl = DIR IMAP：包含SSL支持。 DIR是OpenSSL安装前缀
  --with-interbase = DIR包含Firebird支持。 DIR是火鸟基地
                          安装目录/ opt / firebird
--enable-intl启用国际化支持
  --with-icu-dir = DIR指定可以找到ICU库和头文件的位置
  --disable-json禁用JavaScript对象序列化支持
  --with-ldap = DIR包含LDAP支持
  --with-ldap-sasl = DIR LDAP：包括赛勒斯SASL支持
  --enable-mbstring启用多字节字符串支持
  --disable-mbregex MBSTRING：禁用多字节正则表达式支持
   - 禁用mbregex，原路返回
                          MBSTRING：禁用多字节正则表达式回溯检查
  --with-libmbfl = DIR MBSTRING：使用外部libmbfl。 DIR是libmbfl的基础
                          安装目录BUNDLED
  --with-onig = DIR MBSTRING：使用外部的oniguruma。 DIR是oniguruma安装前缀。
                          如果没有设置DIR，将使用捆绑的oniguruma
  --with-mysqli = FILE包含MySQLi支持。 FILE是路径
                          到mysql_config。如果没有值或mysqlnd传递
                          作为FILE，将使用MySQL本地驱动程序
  --enable-嵌入的mysqli
                          MYSQLi：启用嵌入式支持
                          注意：不适用于MySQL本地驱动程序！
  --with MySQL的-袜子= SOCKPATH
                          MySQLi / PDO_MYSQL：MySQL unix套接字指针的位置。
                          如果未指定，则搜索默认位置
  --with-oci8 = DIR包含Oracle数据库OCI8支持。 DIR默认为$ ORACLE_HOME。
                          使用--with-oci8 = instantclient，/ path / to / instant / client / lib
                          使用Oracle Instant Client安装
  --with-odbcver = HEX强制支持传入的ODBC版本。预计为十六进制数字，默认为0x0350。
                             使用特殊值0来防止显式ODBCVER被定义。
  --with-adabas = DIR包含Adabas D支持/ usr / local
  --with-sapdb = DIR包括SAP DB支持/ usr / local
  --with-solid = DIR包括固体支持/ usr / local / solid
  --with-ibm-db2 = DIR包括IBM DB2支持/ home / db2inst1 / sqllib
  --with-ODBCRouter = DIR包括ODBCRouter.com支持/ usr
  --with-empress = DIR包含Empress支持\ $ EMPRESSPATH
                          （Empress Version> = 8.60）
  --with-皇后-BCS = DIR
                          包括Empress本地访问支持\ $ EMPRESSPATH
                          （Empress Version> = 8.60）
  --with-birdstep = DIR包括Birdstep支持/ usr / local / birdstep
  --with-custom-odbc = DIR包含用户定义的ODBC支持。 DIR是ODBC安装基础
                          目录/ usr / local。确保定义CUSTOM_ODBC_LIBS和
                          在你的include dirs中有一些odbc.h。 F.E.你应该定义
                          以下针对QNX上的Sybase SQL Anywhere 5.5.00
                          运行这个配置脚本：
                            CPPFLAGS = \“ - DODBC_QNX -DSQLANY_BUG \”
                            LDFLAGS = -lunix
                            CUSTOM_ODBC_LIBS = \“ - ldblib -lodbc \”
--with-iodbc = DIR包含iODBC支持/ usr / local
  --with-esoob = DIR包括Easysoft OOB支持/ usr / local / easysoft / oob / client
  --with-unixODBC = DIR包含unixODBC支持/ usr / local
  --with-dbmaker = DIR包含DBMaker支持
  --disable-opcache禁用Zend OPcache支持
  --disable-opcache-file禁用基于文件的缓存
   - 禁用庞大的代码的页面
                          禁用将PHP CODE页面复制到巨大页面中
  --enable-pcntl启用pcntl支持（仅限CLI / CGI）
  --disable-pdo禁用PHP数据对象支持
  --with-pdo-dblib = DIR PDO：DBLIB-DB支持。 DIR是FreeTDS主目录
  --with-pdo-firebird = DIR PDO：Firebird支持。 DIR是火鸟基地
                          安装目录/ opt / firebird
  --with-pdo-mysql = DIR PDO：MySQL支持。 DIR是MySQL的基本目录
                          如果没有值或mysqlnd作为DIR传递，那么
                          将使用MySQL本地驱动程序
  --with-zlib-dir = DIR PDO_MySQL：设置libz安装前缀的路径
  --with-pdo-oci = DIR PDO：Oracle OCI支持。 DIR默认为$ ORACLE_HOME。
                          使用--with-pdo-oci = instantclient，/ path / to / instant / client / lib
                          用于Oracle即时客户端安装。
  --with-PDO-ODBC =风味，DIR
                          PDO：支持'风味'ODBC驱动程序。
        include和lib目录在'dir'下查找。

        'flavor'可以是以下之一：ibm-db2，iODBC，unixODBC，generic
        如果'，dir'部分被省略，则默认为风格
        你已经选择将被使用。例如。：

          --with-PDO-ODBC =的unixODBC

        将检查/ usr / local下的unixODBC。你可以尝试
        使用\“通用\”使用不支持的驱动程序
        味道。通用ODBC支持的语法是：

          --with-PDO-ODBC =通用的，DIR，LIBNAME，LDFLAGS，CFLAGS
构建为“共享”时，扩展名文件名始终为pdo_odbc.so
  --with-pdo-pgsql = DIR PDO：PostgreSQL支持。 DIR是PostgreSQL的基础
                          安装目录或pg_config的路径
  --without-PDO-源码= DIR
                          PDO：sqlite 3支持。 DIR是sqlite的基础
                          安装目录BUNDLED
  --with-pgsql = DIR包含PostgreSQL支持。 DIR是PostgreSQL
                          基本安装目录或pg_config的路径
  --disable-phar禁用phar支持
  --disable-posix禁用类似POSIX的功能
  --with-pspell = DIR包含PSPELL支持。
                          GNU Aspell版本需要0.50.0或更高版本
  --with-libedit = DIR包含libedit readline替换（仅限CLI / CGI）
  --with-readline = DIR包含readline支持（仅限CLI / CGI）
  --with-recode = DIR包括重新编码支持
  --disable-session禁用会话支持
  --with-mm = DIR会话：包括对会话存储的mm支持
  --enable-shmop启用shmop支持
  --disable-simplexml禁用SimpleXML支持
  --with-libxml-dir = DIR SimpleXML：libxml2安装前缀
  --with-snmp = DIR包含SNMP支持
  --with-openssl-dir = DIR SNMP：openssl安装前缀
  --enable-soap启用SOAP支持
  --with-libxml-dir = DIR SOAP：libxml2安装前缀
  --enable-sockets启用套接字支持
  --with-sodium = DIR包括钠支持
  --with-password-argon2 = DIR在password_ *中包含Argon2支持。 DIR是Argon2共享库路径]
  --enable-sysvmsg启用sysvmsg支持
  --enable-sysvsem启用System V信号量支持
  --enable-sysvshm启用System V共享内存支持
  --with-tidy = DIR包含TIDY支持
  --disable-tokenizer禁用标记器支持
  --enable-wddx启用WDDX支持
  --with-libxml-dir = DIR WDDX：libxml2安装前缀
  --with-libexpat-dir = DIR WDDX：用于XMLRPC-EPI的libexpat dir（不建议使用）
  --disable-xml禁用XML支持
  --with-libxml-dir = DIR XML：libxml2安装前缀
  --with-libexpat-dir = DIR XML：libexpat安装前缀（不建议使用）
  --disable-xmlreader禁用XMLReader支持
  --with-libxml-dir = DIR XMLReader：libxml2安装前缀
  --with-xmlrpc = DIR包含XMLRPC-EPI支持
  --with-libxml-dir = DIR XMLRPC-EPI：libxml2安装前缀
  --with-libexpat-dir = DIR XMLRPC-EPI：用于XMLRPC-EPI的libexpat dir（不建议使用）
  --with-iconv-dir = DIR XMLRPC-EPI：用于XMLRPC-EPI的iconv目录
  --disable-xmlwriter禁用XMLWriter支持
  --with-libxml-dir = DIR XMLWriter：libxml2安装前缀
  --with-xsl = DIR包含XSL支持。 DIR是libxslt的基础
                          安装目录（需要libxslt> = 1.1.0）
  --enable-zend-test启用zend-test扩展
  --enable-zip包含Zip读/写支持
  --with-zlib-dir = DIR ZIP：设置libz安装前缀的路径
  --with-pcre-dir ZIP：pcre安装前缀
  --with-libzip = DIR ZIP：使用libzip
  --enable-mysqlnd显式启用mysqlnd，将隐式完成
                          当其他分机需要时
   - 禁用mysqlnd压缩支持
                          在mysqlnd中禁用对MySQL压缩协议的支持
  --with-zlib-dir = DIR mysqlnd：设置libz安装前缀的路径

PEAR：
   --with-pear=DIR         在DIR中安装PEAR [PREFIX / lib / php]
  --without-pear          Do not install PEAR

Zend公司：

  --enable-maintainer-zts启用线程安全 - 仅供代码维护人员使用！
   - 禁用直列优化
                          如果构建zend_execute.lo失败，请尝试使用此开关
  --disable-zend-表示是否启用zend信号处理

TSRM：

  --with-TSRM-PTH = PTH的配置
                          使用GNU Pth
  --with-tsrm-st使用SGI的状态线程
  --with-tsrm-pthreads使用POSIX线程（默认）

Libtool程序：

  --enable-shared = PKGS构建共享库默认=是
  --enable-static = PKGS构建静态库默认=是
  --enable-快速安装= PKGS
                          优化快速安装默认=是
  --with-gnu-ld假设C编译器使用GNU ld default = no
  --disable-libtool-lock避免锁定（可能会中断并行构建）
  --with-pic尝试仅使用PIC /非PIC对象default =同时使用
  --with-tags = TAGS自动包含其他配置


一些有影响的环境变量：
  CC C编译器命令
  CFLAGS C编译器标志
  LDFLAGS链接器标志，例如-L <lib dir>如果你有一个库中的
              非标准目录<lib dir>
  LIBS库传递给链接器，例如-l <库>
  CPPFLAGS（目标）C / C ++预处理器标志，例如-I <包括目录>如果
              您在非标准目录中包含标题<include dir>
  CPP C预处理器
  YACC使用的“另一种编译器编译器”实现。
              默认为第一个被发现的程序：`bison -y'，`byacc'，
              `YACC”。
  YFLAGS默认传递给$ YACC的参数列表。
              该脚本会将YFLAGS默认为空字符串以避免出现
              某些make应用程序给出的`-d'的默认值。
  CXX C ++编译器命令
  CXXFLAGS C ++编译器标志
  CXXCPP C ++预处理器

使用这些变量来覆盖`configure'所做的选择或帮助
它找到非标准名称/位置的图书馆和程序。

向程序包提供商报告错误。