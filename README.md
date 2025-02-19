## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Fri Sep 13 06:46:04 UTC 2024
- Auto Sign-in run successful on Sat Sep 14 00:42:53 UTC 2024
- Auto Sign-in run successful on Sun Sep 15 00:49:58 UTC 2024
- Auto Sign-in run successful on Mon Sep 16 00:46:55 UTC 2024
- Auto Sign-in run successful on Tue Sep 17 00:36:34 UTC 2024
- Auto Sign-in run successful on Wed Sep 18 00:43:25 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 00:44:07 UTC 2024
- Auto Sign-in run successful on Fri Sep 20 00:44:01 UTC 2024
- Auto Sign-in run successful on Sat Sep 21 00:43:29 UTC 2024
- Auto Sign-in run successful on Sun Sep 22 00:50:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 23 00:46:06 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 00:45:36 UTC 2024
- Auto Sign-in run successful on Wed Sep 25 00:46:27 UTC 2024
- Auto Sign-in run successful on Thu Sep 26 00:45:11 UTC 2024
- Auto Sign-in run successful on Fri Sep 27 00:45:37 UTC 2024
- Auto Sign-in run successful on Sat Sep 28 00:45:00 UTC 2024
- Auto Sign-in run successful on Sun Sep 29 00:51:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 30 00:48:00 UTC 2024
- Auto Sign-in run successful on Tue Oct  1 00:51:42 UTC 2024
- Auto Sign-in run successful on Wed Oct  2 00:45:32 UTC 2024
- Auto Sign-in run successful on Thu Oct  3 00:45:38 UTC 2024
- Auto Sign-in run successful on Fri Oct  4 00:45:47 UTC 2024
- Auto Sign-in run successful on Sat Oct  5 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct  6 00:50:47 UTC 2024
- Auto Sign-in run successful on Mon Oct  7 00:48:17 UTC 2024
- Auto Sign-in run successful on Tue Oct  8 00:45:24 UTC 2024
- Auto Sign-in run successful on Wed Oct  9 00:45:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 10 00:45:23 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 00:45:27 UTC 2024
- Auto Sign-in run successful on Sat Oct 12 00:44:23 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 00:50:23 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 00:48:08 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 00:46:30 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 00:46:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 00:45:51 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 00:45:50 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 00:45:12 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 00:51:33 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 00:48:29 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 00:46:41 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 00:50:42 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 00:46:21 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 00:18:28 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 00:42:20 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 00:47:38 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 00:46:03 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 00:44:55 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 00:43:52 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 00:44:14 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 00:48:37 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 00:42:47 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 00:47:45 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 00:45:21 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 00:42:50 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 00:42:52 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 00:43:01 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 00:42:41 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 00:41:45 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 00:46:05 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 00:44:13 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 00:42:19 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 00:43:16 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 00:43:20 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 00:46:00 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 00:45:17 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 00:50:02 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 00:48:00 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 00:45:58 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 00:45:16 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 00:45:25 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 00:46:39 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 00:45:25 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 00:50:29 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 00:47:38 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 00:46:21 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 00:46:53 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 00:47:06 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 00:47:23 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 00:45:22 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 00:56:57 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 00:50:27 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 00:48:58 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 00:48:42 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 00:48:32 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 00:47:53 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 00:47:20 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 00:52:58 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 00:50:58 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 00:50:02 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 00:48:39 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 00:48:09 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 00:49:15 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 00:46:24 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 00:53:16 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 00:51:25 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 00:48:18 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 00:45:56 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 00:46:26 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 00:44:02 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 00:43:13 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 00:48:35 UTC 2024
- Auto Sign-in run successful on Mon Dec 23 00:45:33 UTC 2024
- Auto Sign-in run successful on Tue Dec 24 00:43:50 UTC 2024
- Auto Sign-in run successful on Wed Dec 25 00:43:10 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 00:43:19 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 00:43:35 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 00:42:41 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 00:49:10 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 00:45:38 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 00:43:30 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 00:49:26 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 00:43:20 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 00:43:50 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 00:42:55 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 00:48:36 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 00:46:25 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 00:44:22 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 00:44:08 UTC 2025
- Auto Sign-in run successful on Thu Jan  9 00:43:59 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 00:44:59 UTC 2025
- Auto Sign-in run successful on Sat Jan 11 00:44:16 UTC 2025
- Auto Sign-in run successful on Sun Jan 12 00:49:42 UTC 2025
- Auto Sign-in run successful on Mon Jan 13 00:47:41 UTC 2025
- Auto Sign-in run successful on Tue Jan 14 00:41:59 UTC 2025
- Auto Sign-in run successful on Wed Jan 15 00:43:01 UTC 2025
- Auto Sign-in run successful on Thu Jan 16 00:42:41 UTC 2025
- Auto Sign-in run successful on Fri Jan 17 00:42:29 UTC 2025
- Auto Sign-in run successful on Sat Jan 18 00:41:10 UTC 2025
- Auto Sign-in run successful on Sun Jan 19 00:46:29 UTC 2025
- Auto Sign-in run successful on Mon Jan 20 00:43:42 UTC 2025
- Auto Sign-in run successful on Tue Jan 21 00:42:29 UTC 2025
- Auto Sign-in run successful on Wed Jan 22 00:43:43 UTC 2025
- Auto Sign-in run successful on Thu Jan 23 00:43:04 UTC 2025
- Auto Sign-in run successful on Fri Jan 24 00:42:53 UTC 2025
- Auto Sign-in run successful on Sat Jan 25 00:41:37 UTC 2025
- Auto Sign-in run successful on Sun Jan 26 00:44:10 UTC 2025
- Auto Sign-in run successful on Mon Jan 27 00:44:05 UTC 2025
- Auto Sign-in run successful on Tue Jan 28 00:43:03 UTC 2025
- Auto Sign-in run successful on Wed Jan 29 00:42:55 UTC 2025
- Auto Sign-in run successful on Thu Jan 30 00:42:07 UTC 2025
- Auto Sign-in run successful on Fri Jan 31 00:43:04 UTC 2025
- Auto Sign-in run successful on Sat Feb  1 00:46:09 UTC 2025
- Auto Sign-in run successful on Sun Feb  2 00:45:48 UTC 2025
- Auto Sign-in run successful on Mon Feb  3 00:44:28 UTC 2025
- Auto Sign-in run successful on Tue Feb  4 00:43:10 UTC 2025
- Auto Sign-in run successful on Wed Feb  5 00:43:30 UTC 2025
- Auto Sign-in run successful on Thu Feb  6 00:43:46 UTC 2025
- Auto Sign-in run successful on Fri Feb  7 00:43:44 UTC 2025
- Auto Sign-in run successful on Sat Feb  8 00:42:30 UTC 2025
- Auto Sign-in run successful on Sun Feb  9 00:46:46 UTC 2025
- Auto Sign-in run successful on Mon Feb 10 00:44:46 UTC 2025
- Auto Sign-in run successful on Tue Feb 11 00:43:42 UTC 2025
- Auto Sign-in run successful on Wed Feb 12 00:43:55 UTC 2025
- Auto Sign-in run successful on Thu Feb 13 00:43:59 UTC 2025
- Auto Sign-in run successful on Fri Feb 14 00:43:39 UTC 2025
- Auto Sign-in run successful on Sat Feb 15 00:43:08 UTC 2025
- Auto Sign-in run successful on Sun Feb 16 00:48:21 UTC 2025
- Auto Sign-in run successful on Mon Feb 17 00:46:20 UTC 2025
- Auto Sign-in run successful on Tue Feb 18 00:43:33 UTC 2025
- Auto Sign-in run successful on Wed Feb 19 00:44:02 UTC 2025
