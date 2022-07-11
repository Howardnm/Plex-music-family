# 项目尚未正式启动，等凑齐人，征求各方意见后，再正式启动！！

# Plex-music-family

1、通过一起维护p2p音乐同步库，让plex音乐库越来越强大

2、音乐同步库是由我们音乐爱好者共同维护的一个项目，通过携手共建的方式，让我们的音乐库强大起来，让Plex成为我们免费的随身听

3、同步的目的：《一人上传，多人聆听》，减轻每个人的工作量。人越多，工作量越少。这个机制还有一个妙处，像**AI自动化随机缓存**，人数多起来的时候，由于大众口味的影响，热门的歌曲会更主动去缓存。

## 音乐品质

```
- 音乐库采用《择优劣汰》的方式储存，遇到更好的品质，请覆盖替换
- 优先格式：无损flac > 有损mp3 （推荐这两个格式）
- 不接受：如 wav 等等（占空间，性价比低）
```

## 音乐同步库

### 一、同步库部署

1、本项目采用的同步软件为：[resilio sync](https://www.resilio.com/)

2、为了保护**音乐库**，采用两种同步链接：

```
- 读写同步链接：进群身份验证
- 只读同步链接：统计感兴趣的人数，人数够立刻开启
```

### 二、音乐文件规范化

1、采用**《音乐标签》**软件进行规范化：[MusicTag](https://github.com/Howardnm/Plex-music-family/releases/tag/basics)

2、文件名规范：音乐+歌词

```
-文件夹
 周杰伦-最伟大的作品.flac
 周杰伦-最伟大的作品.lrc
 
# 如果是其他版本，请标注（一般，音乐软件下载后就写清楚了）
 周杰伦-最伟大的作品（live）.mp3
 周杰伦-最伟大的作品（**主题曲）.mp3
```

3、**MusicTag规范化：四步骤**

- 第一步：设置打勾，（下图*号**必填**）

- 第二步：歌词规范化

- 第三步：音乐列表（全选），一键批量修改

- 第四步：规范文件名

<img src="https://user-images.githubusercontent.com/55622355/178245221-ae44c705-b7e4-4d87-8922-be0198d68cab.png" alt="QQ截图20220711182347" style="width:400px;" /><img src="https://user-images.githubusercontent.com/55622355/178250457-61edcf71-3b39-4cd9-96d4-6578c493cb80.png" alt="QQ截图20220711190155" style="width:400px;" /><img src="https://user-images.githubusercontent.com/55622355/178245246-73c62f7b-56a6-43a4-b87a-26fcf2a8d8bb.png" alt="QQ截图20220711182532" style="width:400px;" /><img src="https://user-images.githubusercontent.com/55622355/178250894-decb435e-e6af-4025-8d72-1cb8a052db1b.png" alt="image-20220711182137692" style="width:400px;" />


## 音乐下载渠道

- pt站（有条件的话）
- kw音乐（免安装开心版）[kw-music](https://github.com/Howardnm/Plex-music-family/releases/tag/basics)

```
《qq歌单、网易云歌单》导入到《酷我》教程：

```
