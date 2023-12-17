FROM ubuntu:latest
LABEL authors="stephen"

# 安装 git 和其他必要的工具
RUN apt-get update && \
    apt-get install -y git ssh gcc g++ make cmake ninja-build

ENTRYPOINT ["/bin/bash"]