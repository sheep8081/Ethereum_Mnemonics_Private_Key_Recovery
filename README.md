## Ethereum Mnemonics Private Key Brute-force Recovery | 以太坊助记词碰撞器工具 | 以太坊私钥碰撞器恢复工具

<div align="center">

[![Security Status](https://img.shields.io/badge/Security-Offline%20Operation-brightgreen)](https://github.com/sheep8081/Ethereum_Mnemonics_Private_Key_Recovery)
[![Last Update](https://img.shields.io/badge/Last%20Update-March%202025-orange)](https://github.com/sheep8081/Ethereum_Mnemonics_Private_Key_Recovery/commits/main)

🌏 [English](#english) | [中文](#chinese)

</div>

<table>
<tr>
<td width="50%">

## What is this tool?
A high-performance toolkit that systematically tests cryptographic combinations to recover access to Ethereum wallets. Simply add your target addresses to a text file, and the tool will verify millions of possibilities offline using advanced multi-threaded processing.

### Key Features:
- 🔑 Systematic key space verification
- 📝 Advanced mnemonic phrase testing
- 🚄 High-performance multi-threaded processing
- 🔒 100% offline operation - no network connectivity
- 💻 Simple text file input - just add your addresses

Perfect for researchers, developers, and users who need to verify or recover access to their Ethereum wallets.

</td>
<td width="50%">

## 这是什么工具？
这是一款高性能工具包，通过系统测试加密组合来恢复以太坊钱包的访问权限。只需将目标地址添加到文本文件中，该工具就会使用先进的多线程处理离线验证数百万种可能性。

### 主要特点：
- 🔑 系统密钥空间验证
- 📝 高级助记词测试
- 🚄 高性能多线程处理
- 🔒 完全离线运行 - 无网络连接
- 💻 简单文本文件输入 - 仅添加您的地址

适合研究人员、开发者以及需要验证或恢复以太坊钱包访问权限的用户。

</td>
</tr>
</table>

<h2 id="english">Ethereum Address Verification & Recovery Tool</h2>

## ⚠️ Important Usage Information

This is a computational verification tool that tests large numbers of cryptographic combinations against target Ethereum addresses. It works by:

- Systematically generating key combinations in specified ranges
- Converting each key to its corresponding Ethereum address
- Comparing generated addresses against your target addresses
- Recording any matches found during processing

**This tool requires only your Ethereum address(es)** - no need to input private keys or recovery phrases. Simply create a text file with the addresses you want to verify.

## 🎯 Recovery Methods

### 1. Structured Private Key Space Search - 0x1
- Systematically tests private keys starting with 0x1
- Coverage: `0000000000000000000000000000000000000000000000000000000000000001 - 0FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF`
- Optimized multi-threaded processing for maximum performance

### 2. Configurable Range Search - 0xN
- Customizable starting point for key space verification
- Define your own range (e.g., `0000000000000000000000000000000000000000000000000000000001000000 - 0FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF`)
- Specialized for specific key patterns

### 3. BIP39 Mnemonic Verification
- Tests 12-word and 24-word mnemonic combinations
- Implements full BIP39/BIP44 standards
- Generates derived addresses for comprehensive verification

### 4. Random Distribution Verification
- Statistical sampling across the entire key space
- High-performance batch processing
- Optimized for maximum coverage of probable combinations

## 🚀 Quick Start

### Installation

1. Download the required files:
   - `Ethereum_Recovery_Tool_Ultimate_Edition_vX.X.exe`
   - Create an `address.txt` file with your target addresses

### File Architecture
Required files in working directory:
- `Ethereum_Recovery_Tool_Ultimate_Edition_vX.X.exe` (Main program)
- `address.txt` (Target Ethereum addresses, one per line)
- `complete.txt` (Auto-generated when matches are found)
- `debug.log` (Auto-generated performance logging)
- `license.dat` (Full version activation file)

2. Launch the application and ensure `address.txt` is in the same directory.
![image](https://github.com/user-attachments/assets/e629280a-6537-425a-a6a7-dc920cb58db7)

3. Sample `address.txt` for testing:
```
0x7E5F4552091A69125d5DfCb7b8C2659029395Bdf
0x7f7F156a6c3FD9D3f2024DbD37F483608435Ad77
```
![image](https://github.com/user-attachments/assets/edca54eb-ed88-4004-b3bf-27da39708346)

4. Successful verification results appear in `complete.txt`:
![image](https://github.com/user-attachments/assets/2c11a4fb-02b1-45af-b4f9-25c48e6bedac)

## 💻 Technical Implementation

### Verification Process
- **Key Generation**: Systematic or stochastic creation of candidate private keys
- **Address Derivation**: Standard Ethereum address generation from each candidate key
- **Optimized Matching**: High-speed comparison against target address list
- **Multi-threaded Design**: Parallel processing for maximum hardware utilization

### Performance Optimizations
- Memory-efficient operations for extended runtime capability
- Batch processing to minimize computational overhead
- Checkpoint system for resuming interrupted operations
- Progress tracking with estimated completion statistics

## 📁 Ethereum Database (Updated Weekly)
- **Size**: 300+ million Ethereum addresses
- **Format**: Optimized for high-speed lookup operations
- **Update Frequency**: Weekly with new addresses
- **Storage**: ~100GB compressed, compatible with the tool's address format

## ⚠️ Version Information

| Version | Features | Limitations | Contribution |
|---------|----------|-------------|--------|
| Trial | Basic verification | 1M attempts | Free |
| Full | Unlimited verification | None | US$200 |
| Ethereum Database | 300M+ addresses | None | US$100 |

## 💎 Activation Process
1. Join our Telegram community: [International Group](https://t.me/brute_force_cpu)
2. Make contribution payment
3. Send your Hardware ID to the project maintainer: [@Sheep8081](https://t.me/Sheep8081)
   ![image](https://github.com/user-attachments/assets/2b0a0a75-a161-4460-893a-428046de089f)
4. Receive your activation code to unlock the full version capabilities
   ![image](https://github.com/user-attachments/assets/4fb55cfb-e5fa-4fde-84e6-6c434fa5fc91)

## 🔒 Security Features
- **Completely Offline**: Never connects to the internet during operation
- **Local Processing**: All computations performed on your local machine
- **No Data Transmission**: No information is sent outside your computer
- **Memory Protection**: Secure memory handling with automatic clearing
- **Error Recovery**: Automatic safeguards against system crashes

## 📊 Performance Expectations

The effectiveness of this tool depends on:

1. **Hardware Resources**: More CPU cores and faster processors yield better performance
2. **Search Space Size**: The specific ranges being verified affect completion time
3. **Target Count**: Number of addresses being checked against
4. **Memory Allocation**: Available RAM for batch processing operations

The trial version allows evaluation of performance on your specific hardware before upgrading.

---

<h2 id="chinese">以太坊助记词碰撞器工具 | 以太坊私钥碰撞器恢复工具</h2>

## ⚠️ 重要使用信息

这是一款计算验证工具，可针对目标以太坊地址测试大量加密组合。它的工作原理是：

- 在指定范围内系统生成密钥组合
- 将每个密钥转换为其对应的以太坊地址
- 将生成的地址与您的目标地址进行比较
- 记录处理过程中发现的任何匹配项

**此工具仅需要您的以太坊地址** - 无需输入私钥或恢复短语。只需创建一个包含您要验证的地址的文本文件。

## 🎯 恢复方法

### 1. 结构化私钥空间搜索 - 0x1
- 系统测试以0x1开头的私钥
- 覆盖范围：`0000000000000000000000000000000000000000000000000000000000000001 - 0FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF`
- 优化的多线程处理以获得最大性能

### 2. 可配置范围搜索 - 0xN
- 可自定义的密钥空间验证起点
- 定义您自己的范围（例如，`0000000000000000000000000000000000000000000000000000000001000000 - 0FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF`）
- 专门针对特定密钥模式

### 3. BIP39助记词验证
- 测试12个词和24个词的助记词组合
- 实现完整的BIP39/BIP44标准
- 生成派生地址以进行全面验证

### 4. 随机分布验证
- 整个密钥空间的统计抽样
- 高性能批处理
- 针对可能组合的最大覆盖率进行优化

## 🚀 快速开始

### 安装

1. 下载所需文件：
   - `Ethereum_Recovery_Tool_Ultimate_Edition_vX.X.exe`
   - 创建包含目标地址的`address.txt`文件

### 文件结构
工作目录中所需的文件：
- `Ethereum_Recovery_Tool_Ultimate_Edition_vX.X.exe`（主程序）
- `address.txt`（目标以太坊地址，每行一个）
- `complete.txt`（找到匹配项时自动生成）
- `debug.log`（自动生成的性能日志）
- `license.dat`（完整版激活文件）

2. 启动应用程序并确保`address.txt`位于同一目录中。
![image](https://github.com/user-attachments/assets/e5ccdba8-0872-4d4c-a67a-5cae89469978)

3. 用于测试的示例`address.txt`：
```
0x7E5F4552091A69125d5DfCb7b8C2659029395Bdf
0x7f7F156a6c3FD9D3f2024DbD37F483608435Ad77
```
![image](https://github.com/user-attachments/assets/06c1508e-0d5f-448c-9d79-37b459a2508e)

4. 成功的验证结果会出现在`complete.txt`中：
![image](https://github.com/user-attachments/assets/c5fdd202-6b24-4711-8851-3e6b76bbc29f)

## 💻 技术实现

### 验证过程
- **密钥生成**：候选私钥的系统或随机创建
- **地址派生**：从每个候选密钥生成标准以太坊地址
- **优化匹配**：与目标地址列表进行高速比较
- **多线程设计**：并行处理以最大化硬件利用率

### 性能优化
- 内存高效操作，支持长时间运行能力
- 批处理以最小化计算开销
- 检查点系统，可恢复中断的操作
- 进度跟踪，带有估计完成统计

## 📁 以太坊数据库（每周更新）
- **大小**：3亿多个以太坊地址
- **格式**：针对高速查找操作进行了优化
- **更新频率**：每周更新新地址
- **存储**：压缩后约100GB，与工具的地址格式兼容

## ⚠️ 版本信息

| 版本 | 功能 | 限制 | 贡献 |
|---------|----------|-------------|--------|
| 试用版 | 基本验证 | 100万次尝试 | 免费 |
| 完整版 | 无限验证 | 无 | US$200 |
| 以太坊数据库 | 3亿+地址 | 无 | US$100 |

## 💎 激活流程
1. 加入我们的Telegram社区：[中文群组](https://t.me/brute_force_cpu_chinese)
2. 进行贡献付款
3. 将您的硬件ID发送给项目维护者：[@Sheep8081](https://t.me/Sheep8081)
   ![image](https://github.com/user-attachments/assets/87b9075b-1bd9-48a3-993a-e1e0ebf1a0c1)
4. 接收激活码以解锁完整版功能
   ![image](https://github.com/user-attachments/assets/b0a364a8-7af8-4279-98b1-2f6d23e4b56a)

## 🔒 安全特性
- **内存保护**：安全的内存处理，自动清除
- **错误恢复**：防止系统崩溃的自动保护措施

## 💝 FAQ | 常见问题
- 确保通过在Windows操作系统中将区域设置正确设置为中文（简体）来使用中文版本。
 ![image](https://github.com/user-attachments/assets/0092561f-2741-49bd-9946-175f4e6d315c)

## 📖 Technical Overview & Recovery Process | 技术概述与恢复流程

<table>
<tr>
<td width="50%">

### How It Works

This toolkit implements advanced cryptographic verification methods for Ethereum wallets through:

1. **Address Verification Process:**
   - Utilizes deterministic algorithms to generate and test potential key combinations
   - Implements parallel processing across multiple CPU cores
   - Employs memory-efficient batch operations for sustained performance
   - Uses optimized Ethereum address derivation techniques

2. **Why Ethereum Focus:**
   - High value concentration in ETH addresses
   - Single-signature wallet prevalence
   - Standardized derivation path implementation
   - Compatible with major hardware and software wallets

3. **Technical Implementation:**
   - BIP39 protocol compliance
   - Keccak-256 hashing implementation
   - Secp256k1 curve operations
   - Efficient memory management
   - Multi-threaded architecture for maximum performance

4. **Security Measures:**
   - Completely offline verification
   - No external network connections
   - Secure memory handling practices
   - Automatic cleanup of sensitive data

</td>
<td width="50%">

### 工作原理

本工具包通过以下方式实现以太坊钱包的高级加密验证：

1. **地址验证流程：**
   - 使用确定性算法生成和测试潜在的密钥组合
   - 在多个CPU核心上实现并行处理
   - 采用内存效率高的批处理操作以保持性能
   - 使用优化的以太坊地址派生技术

2. **为什么专注于以太坊：**
   - 以太坊地址中高价值集中度
   - 单签名钱包普遍使用
   - 标准化的派生路径实现
   - 与主要硬件和软件钱包兼容

3. **技术实现：**
   - 符合BIP39协议标准
   - Keccak-256哈希实现
   - Secp256k1曲线运算
   - 高效内存管理
   - 多线程架构以实现最大性能

4. **安全措施：**
   - 完全离线验证
   - 无外部网络连接
   - 安全的内存处理实践
   - 自动清理敏感数据

</td>
</tr>
</table>

<table>
<tr>
<td width="50%">

## 💝 Support Our Development

If you find our tool helpful, please consider supporting our ongoing development! Your contribution helps us:

- 🚀 Develop new features
- 🛠️ Maintain and improve existing functionality
- 🎯 Enhance performance
- 💡 Research new verification methods
- 🌐 Provide better support

### Contribution Addresses
- **ETH:** `0x7887b4f269cacdd9c78e474763b038e41b58473b`
- **TRX:** `TDaxNCkfxSWygq1AXzHN6NQiFAnkByU3bC`

*Every contribution helps us make these tools better for everyone!*

</td>
<td width="50%">

## 💝 支持我们的开发

如果您发现我们的工具有所帮助，请考虑支持我们的持续开发！您的贡献将帮助我们：

- 🚀 开发新功能
- 🛠️ 维护和改进现有功能
- 🎯 提升性能
- 💡 研究新的验证方法
- 🌐 提供更好的支持

### 贡献地址
- **ETH:** `0x7887b4f269cacdd9c78e474763b038e41b58473b`
- **TRX:** `TDaxNCkfxSWygq1AXzHN6NQiFAnkByU3bC`

*每一笔贡献都能帮助我们为所有用户打造更好的工具！*

</td>
</tr>
</table>

## 📱 Shared Community Links | 共享社区链接
- 🌍 International Group | 国际群组: https://t.me/brute_force_cpu
- 🇨🇳 Chinese Group | 中文群组: https://t.me/brute_force_cpu_chinese

## 🛡️ Disclaimer | 免责声明

<table>
<tr>
<td width="50%">

This software is provided for verification and recovery purposes only. Users are responsible for ensuring they have legitimate ownership of any addresses they attempt to verify. The tool makes no guarantees about recovery success as this depends on the specific scenario and available information.

</td>
<td width="50%">

本软件仅供验证和恢复目的使用。用户有责任确保他们对尝试验证的任何地址拥有合法所有权。该工具不对恢复成功提供任何保证，因为这取决于具体情况和可用信息。

</td>
</tr>
</table>
