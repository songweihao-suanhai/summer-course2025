# summer-course2025
2025 年算海团队暑期课程相关资料仓库
 ./env-setup.sh
===== 开始安装项目依赖：HYPRE → METIS → MFEM =====
==> 检测到的目录结构：
    项目根目录      : /home/xiangda/workspace/matrixfree-linear-elasticity-operator
    依赖安装根目录   : /home/xiangda/opt
    源码缓存目录     : /home/xiangda/opt/src
==> 检测到的目录结构：
    项目根目录      : /home/xiangda/workspace/matrixfree-linear-elasticity-operator
    依赖安装根目录   : /home/xiangda/opt
    源码缓存目录     : /home/xiangda/opt/src
==> HYPRE 版本          : 2.28.0
==> 安装前缀            : /home/xiangda/opt/hypre
==> 已存在 hypre-2.28.0.tar.gz，跳过下载
==> 配置 & 编译 HYPRE ...
configure: WARNING: unrecognized options: --with-metis, --without-internal-metis
configure: NOTE: Could not find .git directory
checking build system type... aarch64-unknown-linux-gnu
checking host system type... aarch64-unknown-linux-gnu
checking for mpxlc... no
checking for mpixlc... no
checking for mpiicc... no
checking for mpiicx... no
checking for mpigcc... no
checking for mpicc... mpicc
checking for mpxlC... no
checking for mpixlcxx... no
checking for mpixlC... no
checking for mpiicpc... no
checking for mpiicpx... no
checking for mpig++... no
checking for mpic++... mpic++
checking whether make sets $(MAKE)... yes
checking for ranlib... ranlib
checking whether the C compiler works... no
configure: error: in `/home/xiangda/opt/src/hypre-2.28.0/src':
configure: error: C compiler cannot create executables
See `config.log' for more details
❌ configure 失败
[系统未激活][root@localhost ops]# mpic++ --version
clang version 12.0.1 (kylinsec 12.0.1-6.ky3_5.kb1 0ea4acb4ca019c1c5346adf43186a6be48dbde90)
Target: aarch64-unknown-linux-gnu
Thread model: posix
InstalledDir: /usr/bin


which mpicc
/usr/bin/mpicc
[系统未激活][root@localhost src]# mpicc -show
clang -fprofile-use=/home/abuild/rpmbuild/BUILD/merged.profdata -fPIC -Wl,-z,noexecstack -I/usr/include/mpich-aarch64 -L/usr/lib64/mpich/lib -Wl,-rpath -Wl,/usr/lib64/mpich/lib -Wl,--enable-new-dtags -lmpi


