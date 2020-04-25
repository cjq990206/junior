# 需求规格说明书 Latex 指南
---

## 1、文件结构

>junior

![][1] 

- `demo.tex` 主文件
- `demo.pdf` pdf示例

>chapters

![image_1e6ougumk3vl59f1u4l1mi7u74m.png-7.1kB][2]

- `business.tex` 业务需求分析
- `user.tex` 用户需求分析
- `function.tex` 功能性需求分析
- `nonfunction.tex` 非功能性需求分析

>image

- `b1.png` `u1.png` `f1.png` `n1.png` 图片命名规范 

---
## 2、基本介绍

- 标题

```tex
\section{标题一}
\subsection{标题二}
\subsubsection{标题三}
```

- 图片
```tex
\begin{figure}[!htb]
	\centering
	\includegraphics[scale=1]{image/logo1.png} %修改路径下图片名称 scale 图片缩放
	\caption{北京交通大学校徽} %修改图例（图片标题）
\end{figure}
```

- 表格

表格有需要找TQ

  [1]: http://static.zybuluo.com/TangWill/ubcwsvy6vx2kacdoofotiame/image_1e6oudr7a1e9j1smv1jpif5rsqq9.png
  [2]: http://static.zybuluo.com/TangWill/aend0odou98uaowcq838ue17/image_1e6ougumk3vl59f1u4l1mi7u74m.png