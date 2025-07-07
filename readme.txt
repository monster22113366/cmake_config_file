launch.json:
修改"executable": "${workspaceRoot}/build/CIMC_MODE.elf",

Cmakelist:
修改项目名称

openocd.cfg:
修改set FIRMWARE_PATH build/CIMC_MODE.bin

run.sh:
修改：
elf_file="CIMC_MODE.elf"
bin_file="CIMC_MODE.bin"
hex_file="CIMC_MODE.hex"