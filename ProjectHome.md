> This is a complete example for android-rtmp-client. Now you can download the whole project from Downloads tab.

> android-recorder是为演示android-rtmp-client库在android上的使用而创建的项目，这只是一个功能演示，而不是一个完整的产品。每一次迭代过程中的代码和相关工具都已打包上传到 Downloads下。
<blockquote>Main change of each version：<br>
<blockquote><ol>
<blockquote><li> Get PCM data from mic. </li>
<li> Encode with speex.</li>
<li> Package in flv format.</li>
<li> Publish audio to server.</li>
<li> Record both local and server side.</li>
<li> Play server side file with rtmp protocol on android.</li>
</blockquote></ol>
</blockquote>
<blockquote>主要包括下面几次迭代过程:<br>
<ol>
<blockquote><li> 使用android中的AudioRecord类，获取原始PCM数据. </li>
<li> 将PCM数据用speex编码.</li>
<li> 将编码后的数据打包录制成flv文件.</li>
<li> 使用android-rtmp-client库将编码，打包后的数据直接发布到流媒体服务器.</li>
<li> 本地与服务器端录音同时进行.</li>
<li> 在手机上通过rtmp协议回放服务器端录好的文件.</li>
</blockquote></ol>
</blockquote>