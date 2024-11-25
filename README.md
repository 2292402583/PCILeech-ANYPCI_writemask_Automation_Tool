该项目旨在自动化测试任意PCI设备的配置空的可读写性



已知BUG MSI能力区域由于复位的特殊性会造成错误的将寄存器识别为不可写，因此此工具，用于完成你百分之70%的测试工作，进一步测试请移步视频教程。


（R/W,BIT MASK)【DMA固件之writemask真实值探测脚本使用教程】 【DMA固件制作进阶之任意PCI设备writemask提取与验证。-哔哩哔哩】 https://b23.tv/11twD5Y

PCIe Configuration Space Automation Tool
Overview
The PCIe Configuration Space Automation Tool is designed to automate the testing of read and write capabilities for the configuration space of any PCI device. Leveraging the powerful ARBOR Python API, this tool facilitates comprehensive and efficient validation of PCI configuration registers.

Key Features
Automated Testing: Streamlines the read and write testing of PCI configuration spaces, reducing manual efforts and minimizing errors.

User-Controlled Operations: Offers flexibility for users to skip or perform tests, ensuring complete control over the testing process.

Detailed Logging: Generates comprehensive reports and logs, making it easier to track and analyze test results.

Little-Endian Conversion: Accurately converts data to little-endian format, adhering to PCIe standards.

Error Handling: Includes robust error handling to maintain stability and reliability during operations.

Known Bug
There is a known bug in the MSI capability area due to reset peculiarities, which may incorrectly identify registers as non-writable. As such, this tool can cover approximately 70% of your testing work. For further testing, please refer to the video tutorials.

How It Works


![@SU%`GL29U 0 776$P${XFF](https://github.com/user-attachments/assets/3164205e-412a-4229-9b32-d91d64027bce)

![F7)YG0U)UI3K0OC_6CW2 D7](https://github.com/user-attachments/assets/c8ac7df7-26ce-4474-8930-3a2e902d2100)
