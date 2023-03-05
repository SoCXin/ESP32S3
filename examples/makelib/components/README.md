# Hello World 

在使能IDF环境后(详见idf环境配置)，通过idf.py menuconfig 配置工程可以生成依赖的文件，例如 build/config/sdkconfig.h

然后，在此路径下 make 可以生成 hello_world.a文件，然后将该文件复制到lib/ 并修改文件名为 libhello_world.a

