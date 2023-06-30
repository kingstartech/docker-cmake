FROM openeuler/openeuler:20.03
# repo

# COPY openEuler.repo /etc/yum.repos.d/

# Commands to update the image
RUN dnf update -y
RUN dnf install libaio.x86_64 libnsl.x86_64 openssl-devel libssh2 boost-thread make cmake3 gcc gcc-c++ gcc-base-debuginfo gcc-debuginfo libgcc libstdc++-devel gdb.x86_64 gdb-debuginfo.x86_64 gdb-help.noarch -y

# LANG,LOCALTIME
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

# End
RUN dnf clean all
