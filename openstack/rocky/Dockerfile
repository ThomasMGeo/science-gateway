FROM rockylinux:9.2.20230513

###
# Update the system. Install stuff.
###

# Install repo: Extra Packages for Enterprise Linux
RUN yum upgrade -y && yum install -y epel-release

# Desired packages for basic use
RUN yum install -y sudo man man-pages vim nano git wget unzip ncurses procps \
	htop python3 telnet openssh openssh-clients openssl findutils diffutils

CMD echo 'Build successful! For interactive mode, run as "docker run -it unidata/rocky /bin/bash"'
