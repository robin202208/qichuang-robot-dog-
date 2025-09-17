 Qichuang Robot Dog SDK

Qichuang robot dog 是一个开源的机器狗控制SDK，支持健康检查、动作执行、速度控制、定时移动等基础功能，并扩展AI语音控制能力。  
本项目采用 C++ 编写，支持开发者快速集成与二次开发。

功能特点

- 健康检查接口
- 动作执行（基于动作ID）
- 速度控制与定时移动
- 错误处理标准化
- AI语音控制集成（可扩展）
- 丰富的文档与示例

快速开始
环境准备

- C++17 及以上
- CMake 3.10+
- 推荐系统：Linux/macOS/WSL

编译

```bash
git clone https://github.com/robin202208/qichuang-robot-dog.git
cd qichuang-robot-dog
mkdir build && cd build
cmake ..
make
```

运行示例

```bash
./example/qichuang_example
```

文档

- [API文档](docs/api.md)
- [贡献指南](CONTRIBUTING.md)
- [测试说明](docs/testing.md)

 许可协议

MIT License
