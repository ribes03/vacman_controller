FROM centos:7

WORKDIR /build
COPY . .

RUN yum -y update

# The options are to install faster.
RUN yum -y install \
  --setopt=deltarpm=0 \
  --setopt=install_weak_deps=false \
  --setopt=tsflags=nodocs \
  git \
  gcc \
  make \
  centos-release-scl

RUN yum -y install \
  --setopt=deltarpm=0 \
  --setopt=install_weak_deps=false \
  --setopt=tsflags=nodocs \
  rh-ruby23 \
  rh-ruby23-ruby-devel \
  rh-ruby23-rubygems