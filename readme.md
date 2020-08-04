## 慕课网离线视频合并工具

工具下载：[merger](https://github.com/necan/iMoocMerger/releases)

使用前提：电脑必须联网，用于获取课程信息来创建目录结构。

使用步骤：

1. 在安卓机或 MuMu 模拟器上安装慕课网 app 并下载你购买的视频。

2. 视频位于 SD 卡下的 `Android/data/cn.com.open.mooc/video` 中，其中 `sz_` 开头的文件夹存放的是实战课程，`mf_` 开头的是免费课程，`lj_` 开头的是金职位课程。

   ![image-20200223170937107](assets/image-20200223170937107.png)

3. 视频文件夹中：除了视频文件 `*.ts`，`down.m3u8` 和 `key.hxk` 文件缺一不可，如果缺少，请检查是哪一个 `*.all` 文件夹中缺少，删除它，然后重新下载。

   ![image-20200306181705365](assets/image-20200306181705365.png)

4. 在电脑上创建 `src` 文件夹，将你要合并的 `sz_*` 、`mf_*` 或 `lj_*` 文件夹复制到 `src` 中，下载我提供的合并工具 `merger.exe`，将 `merger.exe` 放在 `src` 同级目录下。

   <img src="assets/image-20200416162205777.png" alt="image-20200416162205777" width="550px" />

5. 双击 `merge.exe`，等待合并完成，合并完的视频在 `merged` 文件夹下。

