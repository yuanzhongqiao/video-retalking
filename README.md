<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div align="center" dir="auto">
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VideoReTalking</font></font><br> <span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于音频的唇形同步，用于野外头戴式视频编辑</font></font></span> </h2><a id="user-content-videoretalking--audio-based-lip-synchronization-for-talking-head-video-editing-in-the-wild-" class="anchor" aria-label="永久链接：VideoReTalking 基于音频的唇形同步，用于野外头部视频编辑" href="#videoretalking--audio-based-lip-synchronization-for-talking-head-video-editing-in-the-wild-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div> 
<p dir="auto"><a href="https://arxiv.org/abs/2211.14758" rel="nofollow"><img src="https://camo.githubusercontent.com/1e74403fdbe7ef492198e92bcb8aba19f0dfef14fe9529c15d6bf24ca6cd3aeb/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41725869762d323231312e31343735382d726564" data-canonical-src="https://img.shields.io/badge/ArXiv-2211.14758-red" style="max-width: 100%;"></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://vinthony.github.io/video-retalking/" rel="nofollow"><img src="https://camo.githubusercontent.com/cf1dae2363e32d85c846383e22e7fd74184899e8ff50223697bd5b026fd43330/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50726f6a6563742d506167652d477265656e" data-canonical-src="https://img.shields.io/badge/Project-Page-Green" style="max-width: 100%;"></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://colab.research.google.com/github/vinthony/video-retalking/blob/main/quick_demo.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://replicate.com/cjwbw/video-retalking" rel="nofollow"><img src="https://camo.githubusercontent.com/80cbd5d14babfb947bdab9317d5e6fc7a4f4332112198213b281e8ac92ec25d5/68747470733a2f2f7265706c69636174652e636f6d2f636a7762772f766964656f2d726574616c6b696e672f6261646765" alt="复制" data-canonical-src="https://replicate.com/cjwbw/video-retalking/badge" style="max-width: 100%;"></a></p>
<div dir="auto">
    Kun Cheng <sup>*,1,2</sup> &emsp;
    <a href="https://vinthony.github.io/" rel="nofollow">Xiaodong Cun <sup>*,2</sup></a>&emsp;
    <a href="https://yzhang2016.github.io/yongnorriszhang.github.io/" rel="nofollow">Yong Zhang <sup>2</sup></a>&emsp;
    <a href="https://menghanxia.github.io/" rel="nofollow">Menghan Xia <sup>2</sup></a>&emsp;
    <a href="https://feiiyin.github.io/" rel="nofollow">Fei Yin <sup>2,3</sup></a>&emsp;<br>
    <a href="https://web.xidian.edu.cn/mrzhu/en/index.html" rel="nofollow">Mingrui Zhu <sup>1</sup></a>&emsp;
    <a href="https://xuanwangvc.github.io/" rel="nofollow">Xuan Wang <sup>2</sup></a>&emsp;
    <a href="https://juewang725.github.io/" rel="nofollow">Jue Wang <sup>2</sup></a>&emsp;
    <a href="https://web.xidian.edu.cn/nnwang/en/index.html" rel="nofollow">Nannan Wang <sup>1</sup></a>
</div>
<br>
<div dir="auto">
    <sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">西安电子科技大学 &emsp; </font></font><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">腾讯人工智能实验室 &emsp; </font></font><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">清华大学
</font></font></div>
<br>
<i><strong><a href="https://sa2022.siggraph.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SIGGRAPH 亚洲 2022 会议轨迹</font></font></a></strong></i>
<br>
<br>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/3c044b086f1050830f1e624833f3d511037dbb6c471136b3a18a95ea6ca27b43/68747470733a2f2f6f70656e74616c6b65722e6769746875622e696f2f766964656f2d726574616c6b696e672f7374617469632f696d616765732f7465617365722e706e67"><img src="https://camo.githubusercontent.com/3c044b086f1050830f1e624833f3d511037dbb6c471136b3a18a95ea6ca27b43/68747470733a2f2f6f70656e74616c6b65722e6769746875622e696f2f766964656f2d726574616c6b696e672f7374617469632f696d616765732f7465617365722e706e67" width="768px" data-canonical-src="https://opentalker.github.io/video-retalking/static/images/teaser.png" style="max-width: 100%;"></a>
<div align="justify" dir="auto">  <br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们推出了 VideoReTalking，这是一种新系统，可以根据输入音频编辑现实世界中头部说话视频的面孔，即使具有不同的情绪，也能生成高质量且口型同步的输出视频。</font><font style="vertical-align: inherit;">我们的系统将这一目标分解为三个连续的任务：
</font></font><p dir="auto"><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(1) 具有规范表情的面部视频生成
</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(2) 音频驱动的口型同步和
</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(3) 用于提高照片真实感的面部增强。</font></font></p>
<p dir="auto"><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">  给定一个头部说话的视频，我们首先使用表情编辑网络根据相同的表情模板修改每一帧的表情，从而产生具有规范表情的视频。</font><font style="vertical-align: inherit;">然后将该视频与给定的音频一起输入到口型同步网络以生成口型同步视频。</font><font style="vertical-align: inherit;">最后，我们通过身份感知面部增强网络和后处理来提高合成面部的照片真实感。</font><font style="vertical-align: inherit;">我们对所有三个步骤都使用基于学习的方法，并且我们的所有模块都可以在顺序管道中处理，无需任何用户干预。</font></font></p></div>
<br><p dir="auto"></p>
<p dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/OpenTalker/video-retalking/blob/main/docs/static/images/pipeline.png?raw=true"><img alt="管道" src="/OpenTalker/video-retalking/raw/main/docs/static/images/pipeline.png?raw=true" width="768px" style="max-width: 100%;"></a><br>
<em align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管道</font></font></em>
</p>
</div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">野外结果（含音频）</font></font></h2><a id="user-content-results-in-the-wild-contains-audio" class="anchor" aria-label="永久链接：野外结果（包含音频）" href="#results-in-the-wild-contains-audio"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<details open="" class="details-reset border rounded-2">
  <summary class="px-3 py-2">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-device-camera-video">
    <path d="M16 3.75v8.5a.75.75 0 0 1-1.136.643L11 10.575v.675A1.75 1.75 0 0 1 9.25 13h-7.5A1.75 1.75 0 0 1 0 11.25v-6.5C0 3.784.784 3 1.75 3h7.5c.966 0 1.75.784 1.75 1.75v.675l3.864-2.318A.75.75 0 0 1 16 3.75Zm-6.5 1a.25.25 0 0 0-.25-.25h-7.5a.25.25 0 0 0-.25.25v6.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-6.5ZM11 8.825l3.5 2.1v-5.85l-3.5 2.1Z"></path>
</svg>
    <span aria-label="视频说明 Results_in_the_wild.mp4" class="m-1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">结果_in_the_wild.mp4</font></font></span>
    <span class="dropdown-caret"></span>
  </summary>

  <video src="https://private-user-images.githubusercontent.com/4397546/224310754-665eb2dd-aadc-47dc-b1f9-2029a937b20a.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDk3OTUxNTQsIm5iZiI6MTcwOTc5NDg1NCwicGF0aCI6Ii80Mzk3NTQ2LzIyNDMxMDc1NC02NjVlYjJkZC1hYWRjLTQ3ZGMtYjFmOS0yMDI5YTkzN2IyMGEubXA0P1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDMwNyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDAzMDdUMDcwMDU0WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NTYzOWY1MGE0NjBlOGFmOWRjYTlmMDVlM2MwYzk1MzE0NjQ1ZDQ1ZjU0NjVmY2M4MWI0ZGJlZmE0Nzg2MzU3NyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.ujxOULCpalS8QZnNrRLZ24l4U98I3xMC1tWlwBLWQyk" data-canonical-src="https://private-user-images.githubusercontent.com/4397546/224310754-665eb2dd-aadc-47dc-b1f9-2029a937b20a.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDk3OTUxNTQsIm5iZiI6MTcwOTc5NDg1NCwicGF0aCI6Ii80Mzk3NTQ2LzIyNDMxMDc1NC02NjVlYjJkZC1hYWRjLTQ3ZGMtYjFmOS0yMDI5YTkzN2IyMGEubXA0P1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDMwNyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDAzMDdUMDcwMDU0WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NTYzOWY1MGE0NjBlOGFmOWRjYTlmMDVlM2MwYzk1MzE0NjQ1ZDQ1ZjU0NjVmY2M4MWI0ZGJlZmE0Nzg2MzU3NyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.ujxOULCpalS8QZnNrRLZ24l4U98I3xMC1tWlwBLWQyk" controls="controls" muted="muted" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px; min-height: 200px">

  </video>
</details>

<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境</font></font></h2><a id="user-content-environment" class="anchor" aria-label="永久链接：环境" href="#environment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://github.com/vinthony/video-retalking.git
cd video-retalking
conda create -n video_retalking python=3.8
conda activate video_retalking

conda install ffmpeg

# Please follow the instructions from https://pytorch.org/get-started/previous-versions/
# This installation command only works on CUDA 11.1
pip install torch==1.9.0+cu111 torchvision==0.10.0+cu111 -f https://download.pytorch.org/whl/torch_stable.html

pip install -r requirements.txt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/vinthony/video-retalking.git
cd video-retalking
conda create -n video_retalking python=3.8
conda activate video_retalking

conda install ffmpeg

# Please follow the instructions from https://pytorch.org/get-started/previous-versions/
# This installation command only works on CUDA 11.1
pip install torch==1.9.0+cu111 torchvision==0.10.0+cu111 -f https://download.pytorch.org/whl/torch_stable.html

pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速推理</font></font></h2><a id="user-content-quick-inference" class="anchor" aria-label="永久链接：快速推理" href="#quick-inference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预训练模型</font></font></h4><a id="user-content-pretrained-models" class="anchor" aria-label="永久链接：预训练模型" href="#pretrained-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请下载我们</font></font><a href="https://drive.google.com/drive/folders/18rhjMpxK8LVVxf7PI6XwOidt8Vouv_H0?usp=share_link" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预先训练的模型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并将其放入</font></font><code>./checkpoints</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>

<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推理</font></font></h4><a id="user-content-inference" class="anchor" aria-label="永久链接： 推理" href="#inference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 inference.py \
  --face examples/face/1.mp4 \
  --audio examples/audio/1.wav \
  --outfile results/1_1.mp4
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 inference.py \
  --face examples/face/1.mp4 \
  --audio examples/audio/1.wav \
  --outfile results/1_1.mp4" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该脚本包括数据预处理步骤。</font><font style="vertical-align: inherit;">您可以测试任何说话的脸部视频，无需手动对齐。</font><font style="vertical-align: inherit;">但值得注意的是，DNet 无法处理极端姿势。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以通过添加以下参数来控制表达式：</font></font></p>
<p dir="auto"><code>--exp_img</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：预定义的表达式模板。</font><font style="vertical-align: inherit;">默认为“中性”。</font><font style="vertical-align: inherit;">您可以选择“微笑”或图像路径。</font></font></p>
<p dir="auto"><code>--up_face</code><font style="vertical-align: inherit;"></font><a href="https://github.com/donydchen/ganimation_replicate"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：您可以选择“惊讶”或“愤怒”来用GANimation</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来修改上脸的表情</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h2><a id="user-content-citation" class="anchor" aria-label="永久链接：引文" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现我们的工作对您的研究有用，请考虑引用：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@misc{cheng2022videoretalking,
        title={VideoReTalking: Audio-based Lip Synchronization for Talking Head Video Editing In the Wild}, 
        author={Kun Cheng and Xiaodong Cun and Yong Zhang and Menghan Xia and Fei Yin and Mingrui Zhu and Xuan Wang and Jue Wang and Nannan Wang},
        year={2022},
        eprint={2211.14758},
        archivePrefix={arXiv},
        primaryClass={cs.CV}
  }
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@misc{cheng2022videoretalking,
        title={VideoReTalking: Audio-based Lip Synchronization for Talking Head Video Editing In the Wild}, 
        author={Kun Cheng and Xiaodong Cun and Yong Zhang and Menghan Xia and Fei Yin and Mingrui Zhu and Xuan Wang and Jue Wang and Nannan Wang},
        year={2022},
        eprint={2211.14758},
        archivePrefix={arXiv},
        primaryClass={cs.CV}
  }" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h2><a id="user-content-acknowledgement" class="anchor" aria-label="永久链接：致谢" href="#acknowledgement"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢
</font></font><a href="https://github.com/Rudrabha/Wav2Lip"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wav2Lip</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://github.com/RenYurui/PIRender"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PIRenderer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://github.com/TencentARC/GFPGAN"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GFP-GAN</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://github.com/yangxy/GPEN"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPEN</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://github.com/donydchen/ganimation_replicate"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ganimation_replicate</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://github.com/rotemtzaban/STIT"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">STIT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
分享他们的代码。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相关工作</font></font></h2><a id="user-content-related-work" class="anchor" aria-label="永久链接：相关工作" href="#related-work"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/FeiiYin/StyleHEAT"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">StyleHEAT：通过预先训练的 StyleGAN 一次性生成高分辨率可编辑说话脸部 (ECCV 2022)</font></font></a></li>
<li><a href="https://github.com/Doubiiu/CodeTalker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CodeTalker：具有离散运动先验的语音驱动 3D 面部动画 (CVPR 2023)</font></font></a></li>
<li><a href="https://github.com/Winfredy/SadTalker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SadTalker：学习用于风格化音频驱动的单图像说话人脸动画的真实 3D 运动系数 (CVPR 2023)</font></font></a></li>
<li><a href="https://github.com/Carlyx/DPE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DPE：解开一般视频肖像编辑的姿势和表情 (CVPR 2023)</font></font></a></li>
<li><a href="https://github.com/FeiiYin/SPI/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有面部对称先验的 3D GAN 反演 (CVPR 2023)</font></font></a></li>
<li><a href="https://github.com/Mael-zys/T2M-GPT"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">T2M-GPT：通过离散表示的文本描述生成人体运动 (CVPR 2023)</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免责声明</font></font></h2><a id="user-content-disclaimer" class="anchor" aria-label="永久链接：免责声明" href="#disclaimer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这不是腾讯的官方产品。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>1. Please carefully read and comply with the open-source license applicable to this code before using it. 
2. Please carefully read and comply with the intellectual property declaration applicable to this code before using it.
3. This open-source code runs completely offline and does not collect any personal information or other data. If you use this code to provide services to end-users and collect related data, please take necessary compliance measures according to applicable laws and regulations (such as publishing privacy policies, adopting necessary data security strategies, etc.). If the collected data involves personal information, user consent must be obtained (if applicable). Any legal liabilities arising from this are unrelated to Tencent.
4. Without Tencent's written permission, you are not authorized to use the names or logos legally owned by Tencent, such as "Tencent." Otherwise, you may be liable for your legal responsibilities.
5. This open-source code does not have the ability to directly provide services to end-users. If you need to use this code for further model training or demos, as part of your product to provide services to end-users, or for similar use, please comply with applicable laws and regulations for your product or service. Any legal liabilities arising from this are unrelated to Tencent.
6. It is prohibited to use this open-source code for activities that harm the legitimate rights and interests of others (including but not limited to fraud, deception, infringement of others' portrait rights, reputation rights, etc.), or other behaviors that violate applicable laws and regulations or go against social ethics and good customs (including providing incorrect or false information, spreading pornographic, terrorist, and violent information, etc.). Otherwise, you may be liable for your legal responsibilities.

</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="1. Please carefully read and comply with the open-source license applicable to this code before using it. 
2. Please carefully read and comply with the intellectual property declaration applicable to this code before using it.
3. This open-source code runs completely offline and does not collect any personal information or other data. If you use this code to provide services to end-users and collect related data, please take necessary compliance measures according to applicable laws and regulations (such as publishing privacy policies, adopting necessary data security strategies, etc.). If the collected data involves personal information, user consent must be obtained (if applicable). Any legal liabilities arising from this are unrelated to Tencent.
4. Without Tencent's written permission, you are not authorized to use the names or logos legally owned by Tencent, such as &quot;Tencent.&quot; Otherwise, you may be liable for your legal responsibilities.
5. This open-source code does not have the ability to directly provide services to end-users. If you need to use this code for further model training or demos, as part of your product to provide services to end-users, or for similar use, please comply with applicable laws and regulations for your product or service. Any legal liabilities arising from this are unrelated to Tencent.
6. It is prohibited to use this open-source code for activities that harm the legitimate rights and interests of others (including but not limited to fraud, deception, infringement of others' portrait rights, reputation rights, etc.), or other behaviors that violate applicable laws and regulations or go against social ethics and good customs (including providing incorrect or false information, spreading pornographic, terrorist, and violent information, etc.). Otherwise, you may be liable for your legal responsibilities.
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢我们的贡献者</font></font></h2><a id="user-content-all-thanks-to-our-contributors" class="anchor" aria-label="永久链接：感谢我们的贡献者" href="#all-thanks-to-our-contributors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<a href="https://github.com/OpenTalker/video-retalking/graphs/contributors">
  <img src="https://camo.githubusercontent.com/818c13f68d8bf06d4946ebe64c67551ca2b8e1757c40ea17cf4fadfd58543575/68747470733a2f2f636f6e747269622e726f636b732f696d6167653f7265706f3d4f70656e54616c6b65722f766964656f2d726574616c6b696e67" data-canonical-src="https://contrib.rocks/image?repo=OpenTalker/video-retalking" style="max-width: 100%;">
</a>
</article></div>
