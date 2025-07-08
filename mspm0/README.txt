(1)使用前提
安装好 cmake  ninja  arm-none-eabi-gcc   arm-none-eabi-gdb  openocd clangd
以及vscode 及它的插件 cortex-debug   clangd

(2) 本地移植
1-修改工程中的工具链目录（一定要改，相关文件中有注释指引）
相关文件：  .vscode/settings.json   .vscode/launch.json  .clangd
2-修改输出的elf文件名称及bin,hex文件名称（可改可不改，改就跟着指导彻底）
相关文件：   CMakeLists.txt 的14行 

（3）使用
#先进入build 并 删除原来的缓存
cd build && rm -rf *
#然后退出，run.sh
cd .. && ./run.sh

