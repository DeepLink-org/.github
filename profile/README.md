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

人工智能开放计算平台-DeepLink，作为芯片与深度学习框架适配的“桥梁”，根本性实现软硬件解耦，建设开放的软硬件适配生态。遵守此标准可以实现主流框架与芯片高效适配，极大降低算力使用门槛，减少技术阻力。从而打破算力和框架的垄断，实现算力要素多样化。并且通过编译的力量，提升整体的训练效率。基于DeepLink，上下游厂商通过一次适配即可深度接入算法生态，为人工智能软硬上下游合作共建起到关键纽带作用。



<div align="center">
  <img src="./resources/DeepLink03.png" width="500"/>
</div>
<!-- https://deeplink.readthedocs.io/zh_CN/latest/_images/Deeplink01.png -->

DeepLink支持开源轻量级AI加速框架InternEvo，支持无需大量依赖关系的模型预训练。凭借单一代码库，InternEvo支持在上千GPU的大规模集群上进行预训练，并在单个GPU上进行微调，同时实现显著的性能优化。此外，为提升软硬件适配效率，充分释放芯片算力，DeepLink定义了一套计算统一接口，可有效解耦框架与芯片的适配过程。

目前，DeepLink已与10余家硬件企业展开合作。在多个计算平台实现了多个模型的训练和推理适配。

<!-- DeepLink从人工智能芯片-深度学习框架的适配实践中总结出来，在二者之间定义了一套计算契约，良好的函数抽象使得上游芯片和下游框架两层在适配工程实施时能有效地解耦。与此同时，基于这种实践，还可以将芯片的适配工作复用到不同的训练框架适配中去。接口的标准化定义包含算子接口（DIOPI）和编译接口（DICP）两个部分。 -->