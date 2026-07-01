**CCL2025-基于多样性数据重组增强的藏汉神经机器翻译**

本仓库包含了面向藏汉神经机器翻译（NMT）的多样性数据重组增强（DiRec）方法。该方法旨在解决低资源语言数据稀缺的问题，通过利用LLMs生成多样化的数据，进行成分重组consituent、句型重组mood和风格重组style，以增强平行数据的多样性。


**如果您在您的工作中使用了该数据集，请引用以下论文**：

```
@inproceedings{xue-etal-2025-ji,
    title = "基于多样性数据重组增强的藏汉神经机器翻译",
    author = "Xue, Jiayi  and
      Chen, Jinming  and
      Chen, Bo  and
      Bao, Wei  and
      Zhao, Xiaobing",
    editor = "Sun, Maosong  and
      Duan, Peiyong  and
      Liu, Zhiyuan  and
      Xu, Ruifeng  and
      Sun, Weiwei",
    booktitle = "Proceedings of the 24th {C}hina National Conference on Computational Linguistics ({CCL} 2025)",
    month = aug,
    year = "2025",
    address = "Jinan, China",
    publisher = "Chinese Information Processing Society of China",
    url = "https://aclanthology.org/2025.ccl-1.2/",
    pages = "16--27",
    abstract = "``高资源语言的神经机器翻译虽已取得显著进展,但低资源语言面临更严重的平行数据不足的问题。为此,提出一种面向藏汉神经机器翻译的多样性数据重组增强方法(DiRec)。该方法利用大语言模型的双向语言能力,对已有藏汉平行数据进行成分重组、句型重组和风格重组三种数据重组,经过两轮质量自动筛选后得到多样性增强数据。在藏汉机器翻译的实验中,相较于基线模型,基于DiRec的模型的泛化能力指标提升4.83个百分点,BLEU提高0.55,chrF++提高0.20。最后分析了不同数据重组方式对翻译模型性能的影响。''"
}

```