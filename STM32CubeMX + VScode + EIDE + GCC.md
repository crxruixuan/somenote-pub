# VScode 的配置

## 安装 VScode

VScode 官网：[Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/)

点击下载即可。

​![image](assets/image-20240220123413-rconhc5.png)

为保证权限充足，请不要从浏览器中直接打开安装包，而是从文件管理器中从右键打开。

​![image](assets/image-20240220123627-lcq8yr7.png)![image](assets/image-20240220123956-lezgvf2.png)​

按默认设置安装即可。

## 安装必备插件

​![image](assets/image-20240220124407-4c9zil3.png)​

​![image](assets/image-20240220124516-46se8kz.png)​

​![image](assets/image-20240220144717-ayciwlw.png)​

## 安装 GNU Arm Embedded Toolchain 编译工具链

打开 "Embedded IDE" 插件面板，配置编译工具链，选择 "GNU Arm Embedded Toolchain" ，直接在线下载即可。

​![recording](assets/recording-20240220134620-yy80096.gif)​

## 安装开源调试工具 OpenOCD

​![recording](assets/recording-20240220135318-62548sj.gif)​

# 项目的导入与配置

## 使用 STM32CubeMX 导出工程

需要更改 STM32CubeMX 中的部分设置。

​![image](assets/image-20240220140451-wojdda4.png)​

​![image](assets/image-20240220140558-zooi1vn.png)​

然后点击生成代码。

​![image](assets/image-20240220140637-ra5kldm.png)​

工程就成功导出了。

​![image](assets/image-20240220140745-uftwn7h.png)​

## 导入生成好的工程到 VScode

返回 VScode ，点击 “Import Project” ，选择 “Eclipse” 类型，选择生成代码中的 “.cproject” 文件。

​![recording](assets/recording-20240220141608-fsbsq6z.webp)​

## 配置没有成功导入的部分

1. 配置 LinkerScript（绿色）
2. 把调试器改为 OpenOCD，选择自己的型号（绿色）
3. （若还是无法编译运行，则参考红色部分补充完整）

​![image](assets/image-20240220153235-1je5nx0.png)​

​![PixPin_2024-02-20_14-22-44](assets/PixPin_2024-02-20_14-22-44-20240220142424-f4740hk.webp)​

# 功能测试

## 编译和下载

​![PixPin_2024-02-20_14-38-09](assets/PixPin_2024-02-20_14-38-09-20240220143849-zcclrwz.webp)​

## 调试

​![PixPin_2024-02-20_14-50-21](assets/PixPin_2024-02-20_14-50-21-20240220145128-2phivpc.webp)​

# 推荐的其他插件

​![image](assets/image-20240220145324-pyx7ifj.png)​

​![image](assets/image-20240220145346-dpbshzw.png)​

​![image](assets/image-20240220145359-umd6rk5.png)​

​![image](assets/image-20240220145413-40n7slh.png)​

​![image](assets/image-20240220145509-qtkh2gh.png)​

​![image](assets/image-20240220145622-by0k751.png)​

​![image](assets/image-20240220145647-cx4eypw.png)​

​![image](assets/image-20240220145734-8s8vp5j.png)​

​![image](assets/image-20240220145749-puo2621.png)​

​![image](assets/image-20240220145805-ah525io.png)​

​![image](assets/image-20240220145821-8elzcdj.png)​

​![image](assets/image-20240220145831-jga4nmy.png)​

​![image](assets/image-20240220145848-l0e75qr.png)​

​![image](assets/image-20240220145901-aty1tcx.png)​

​![image](assets/image-20240220145910-as4rvfv.png)​

​![image](assets/image-20240220145926-nneasbp.png)​

​![image](assets/image-20240220145934-zcj4gh2.png)​

​![image](assets/image-20240220145951-51yw6ov.png)​

‍

​​
