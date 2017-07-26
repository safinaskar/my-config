cmake_minimum_required (VERSION 3.0.2) # 3.0.2 подходит
project (my-config LANGUAGES)
install (PROGRAMS my-config-add-line my-config-cat my-config-change-lines my-config-mkdir DESTINATION sbin)
