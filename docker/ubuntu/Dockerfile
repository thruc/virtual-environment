FROM ubuntu:latest

# 日本語化
RUN apt-get update \
  && apt-get install -y locales \ 
  && locale-gen ja_JP.UTF-8 \
  && echo "export LANG=ja_JP.UTF-8" >> ~/.bashrc