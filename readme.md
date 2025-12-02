<!-- 中英切换按钮 -->
<div align="right">
  <button id="btn-zh" onclick="switchLang('zh')">中文</button>
  <button id="btn-en" onclick="switchLang('en')">English</button>
</div>

<!-- 中文区域 -->
<div id="lang-zh" class="lang-section">

# 电子球视频和图片转换工具及使用方法

---
## 下载工具
### 1️⃣ 点击下面的链接下载视频和图片转换工具。
- ⬇️[下载视频转换工具](https://github.com/ZONESTAR3D/eEGG-Tools/releases/tag/VideoConverter-V0.7)
- ⬇️[下载图片转换工具](https://github.com/ZONESTAR3D/eEGG-Tools/releases/tag/ImageConverter-V0.3)

### 2️⃣ 将下载的 ZIP 文件解压缩到您电脑的磁盘中，建议放置到 D 盘或其他磁盘，不要使用中文目录。

---
## 视频转换工具使用说明
1️⃣ 打开视频转换工具应用软件。  
![](./pic/1.png)

2️⃣ 设置转换参数  
- 若设备为 eEGG5，请按下图配置：  
  ![](./pic/2.png)  
- 若设备为 eEGG6 / eEGG7，请按下图配置：  
  ![](./pic/3.png)

3️⃣ 打开需要转换的文件（支持多选）。  
4️⃣ 点击「转换」按钮，转换后的文件将保存在源文件所在目录下的 `output` 文件夹中。文件较多时请耐心等待。  
转换完成后即可将文件上传至设备播放。

---
## 图片转换工具使用说明
1️⃣ 打开图片转换工具应用软件。  
![](./pic/4.png)

2️⃣ 设置显示参数  
- eEGG5 请选择输出尺寸 **240×240**  
- eEGG6 / eEGG7 请选择输出尺寸 **360×360**  
> 勾选「裁剪为圆形」可减小文件体积，设备显示效果相同。

3️⃣ 点击「导入」按钮选择源文件。  
4️⃣ 点击「导出」按钮并输入文件名。  
转换完成后即可将文件上传至设备播放。

</div>

<!-- English section -->
<div id="lang-en" class="lang-section" style="display:none;">

# eEGG Video & Image Converter Tools – Quick Guide

---
## Download
### 1️⃣ Click the links below to download the converters.
- ⬇️[Video Converter](https://github.com/ZONESTAR3D/eEGG-Tools/releases/tag/VideoConverter-V0.7)
- ⬇️[Image Converter](https://github.com/ZONESTAR3D/eEGG-Tools/releases/tag/ImageConverter-V0.3)

### 2️⃣ Unzip the downloaded ZIP to any disk (e.g. D:\). **Avoid Chinese characters in the path.**

---
## Video Converter
1️⃣ Launch the video converter.  
![](./pic/1.png)

2️⃣ Choose settings  
- eEGG5 ➜ use the preset shown below:  
  ![](./pic/2.png)  
- eEGG6 / eEGG7 ➜ use the preset shown below:  
  ![](./pic/3.png)

3️⃣ Add files (multi-select supported).  
4️⃣ Press 「Convert」. Output files will appear in an `output` folder next to the source.  
When finished, upload the files to your device.

---
## Image Converter
1️⃣ Launch the image converter.  
![](./pic/4.png)

2️⃣ Set display parameters  
- eEGG5 ➜ select **240×240**  
- eEGG6 / eEGG7 ➜ select **360×360**  
> Tick「Crop to circle」to reduce file size; visual result on device is identical.

3️⃣ Click「Import」to load source images.  
4️⃣ Click「Export」and enter a file name.  
When finished, upload the files to your device.

</div>

<!-- 极简切换脚本 -->
<script>
  function switchLang(l) {
    document.getElementById('lang-zh').style.display = l === 'zh' ? 'block' : 'none';
    document.getElementById('lang-en').style.display = l === 'en' ? 'block' : 'none';
    document.getElementById('btn-zh').style.fontWeight = l === 'zh' ? 'bold' : 'normal';
    document.getElementById('btn-en').style.fontWeight = l === 'en' ? 'bold' : 'normal';
  }
  // 默认显示中文
  switchLang('zh');
</script>