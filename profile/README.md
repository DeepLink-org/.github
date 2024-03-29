<div align="center">
  <img src="https://deeplink.readthedocs.io/zh_CN/latest/_static/image/logo.png" width="400"/>
  <div>&nbsp;</div>
  <div align="center">
    <b><font size="5">DeepLink website</font></b>
    <sup>
      <a href="http://deeplink.org.cn/home">
        <i><font size="4">HOT</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <b><font size="5">DeepLink documents</font></b>
    <sup>
      <a href="https://deeplink.readthedocs.io/zh_CN/latest/">
        <i><font size="4">Tutorial</font></i>
      </a>
    </sup>
  </div>
  <div>&nbsp;</div>
</div>

DeepLink是一套设备无关的接口体系，作为芯片与深度学习框架适配的“桥梁”，根本性实现软硬件解耦，建设开放的软硬件适配生态。遵守此标准可以实现主流框架与芯片高效适配，极大降低算力使用门槛，减少技术阻力。从而打破算力和框架的垄断，实现算力要素多样化。并且通过编译的力量，提升整体的训练效率。基于DeepLink，上下游厂商通过一次适配即可深度接入算法生态，为人工智能软硬上下游合作共建起到关键纽带作用。

DeepLink从人工智能芯片-深度学习框架的适配实践中总结出来，在二者之间定义了一套计算契约，良好的函数抽象使得上游芯片和下游框架两层在适配工程实施时能有效地解耦。与此同时，基于这种实践，还可以将芯片的适配工作复用到不同的训练框架适配中去。接口的标准化定义包含算子接口（DIOPI）和编译接口（DICP）两个部分。

<div align="center">
  <img src="https://deeplink.readthedocs.io/zh_CN/latest/_images/Deeplink01.png" width="400"/>
</div>
