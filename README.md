# musicWebsite性能优化
1. <strong>减少图片的接口请求 </strong>
&nbsp; 原本的网页图片src均为图片的网络地址，现将其下载以提升性能；
2. <strong>将图片压缩</strong> 
&nbsp; 将网页主要图片进行1%-70%的压缩，从而减少读取和绘制图片的消耗；
3. <strong>图片延迟加载</strong>
&nbsp; 用现代浏览器原生的功能，实现图片的延时加载；      
4. <strong>将静态资源缓存到CDN节点上</strong> 
&nbsp; 
