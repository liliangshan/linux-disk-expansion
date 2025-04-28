# Linux磁盘扩容工具

这是一个用于扩展Linux磁盘分区的工具，支持多种文件系统和分区方案。

## 功能特点

- 支持多种文件系统（ext4, xfs, btrfs等）
- 支持LVM和非LVM分区
- 提供安全的磁盘扩展操作
- 自动检测当前分区状态

## 使用方法

1. 下载工具：
```bash
wget https://github.com/liliangshan/linux-disk-expansion/releases/download/1.0.0/linux-disk-expansion
chmod +x linux-disk-expansion
```

2. 以root权限运行程序：
```bash
sudo ./linux-disk-expansion
```

3. 程序会显示当前分区的使用情况
4. 根据提示进行操作

## 注意事项

- 操作前请务必备份重要数据
- 建议在操作前先测试环境
- 确保有足够的未分配空间用于扩展
- 某些操作可能需要重启系统

## 许可证

MIT License 