<div align="center">
  <img src="https://deeplink.readthedocs.io/zh_CN/latest/_static/image/logo.png" width="400"/>
  <div>&nbsp;</div>
  <div align="center">
    <b><font size="5">Website</font></b>
    <sup>
      <a href="http://deeplink.org.cn/home">
        <i><font size="4">HOT</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <b><font size="5">Documents</font></b>
    <sup>
      <a href="https://deeplink.readthedocs.io/zh_CN/latest/">
        <i><font size="4">Tutorial</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <b><font size="5">Research</font></b>
    <sup>
      <a href="https://deeplink.readthedocs.io/zh_CN/latest/">
        <i><font size="4">HOT</font></i>
      </a>
    </sup>
  </div>
  <div>&nbsp;</div>
</div>

人工智能开放计算平台-DeepLink，作为芯片与深度学习框架适配的“桥梁”，根本性实现软硬件解耦，建设开放的软硬件适配生态。遵守此标准可以实现主流框架与芯片高效适配，极大降低算力使用门槛，减少技术阻力。从而打破算力和框架的垄断，实现算力要素多样化。并且通过编译的力量，提升整体的训练效率。基于DeepLink，上下游厂商通过一次适配即可深度接入算法生态，为人工智能软硬上下游合作共建起到关键纽带作用。

同时，我们定期开展硬件测评工作。硬件评测基于团体标准评测方法，以国际主流芯片的性能作为对标，对送测芯片进行技术规格、软件生态、功能、性能等多维度测试，并按季度产出硬件评测报告。评测结论可为各类国产加速卡在不同维度的表现提供参考。

<div align="center">
  <img src="resources/Deeplink03.png" width="400"/>
</div>

<div align="center">
  <b><font size="3">DeepLink 2.0</font></b>
</div><div align="center">
    <b><font size="2">训练</font></b>
    <sup>
      <a href="https://deeplink.readthedocs.io/zh-cn/latest/doc/TechSupport/train.html">
        <i><font size="1.5">ditorch</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;|&nbsp;&nbsp;
    <b><font size="2">推理</font></b>
    <sup>
      <a href="https://deeplink.readthedocs.io/zh-cn/latest/doc/TechSupport/infer.html">
        <i><font size="1.5">dlinfer</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;|&nbsp;&nbsp;
    <b><font size="2">编译</font></b>
    <sup>
      <a href="">
        <i><font size="1.5">triton(待开源)</font></i>
      </a>
    </sup>
  </div>
DeepLink2.0 从场景支持、互联能力、易用性和性能多方着手升级版图。

1. 支持开源轻量级AI加速框架InternEvo，支持无需大量依赖关系的模型预训练。凭借单一代码库，InternEvo支持在上千GPU的大规模集群上进行预训练，并在单个GPU上进行微调，同时实现显著的性能优化。
2. 上下层共同发力构建triton生态，针对硬件特性进行扩展功能加持。
3. 此外，为提升软硬件适配效率，充分释放芯片算力，DeepLink定义了一套计算统一接口，可有效解耦框架与芯片的适配过程。

目前，DeepLink已与10余家硬件企业展开合作，在多个计算平台实现了多个模型的训练和推理适配。

<!-- DeepLink从人工智能芯片-深度学习框架的适配实践中总结出来，在二者之间定义了一套计算契约，良好的函数抽象使得上游芯片和下游框架两层在适配工程实施时能有效地解耦。与此同时，基于这种实践，还可以将芯片的适配工作复用到不同的训练框架适配中去。接口的标准化定义包含算子接口（DIOPI）和编译接口（DICP）两个部分。 -->