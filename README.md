# TinyChatServer
基于Muduo网络库，利用Nginx实现集群+利用Redis实现消息队列的简易版聊天服务器

## bin
主要包括最终生成的两个可执行文件ChatClient(客户端) 和 ChatServer(服务端)

## build
主要包括编译过程可能生成的一些中间文件，
在bin/目录下执行
~~~
cmake ..
make
~~~
即可编译生成bin/目录下 可执行文件ChatClient(客户端) 和 ChatServer(服务端)

## include
主要包括一些头文件

## src
源代码文件

## thirdparty
用到的第三方库文件，例如项目中用到的json.hpp

## CMakeLists.txt
cmake编译脚本
