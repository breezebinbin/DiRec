**CCL2025-基于多样性数据重组增强的藏汉神经机器翻译**

本仓库包含了面向藏汉神经机器翻译（NMT）的多样性数据重组增强（DiRec）方法。该方法旨在解决低资源语言数据稀缺的问题，通过利用LLMs生成多样化的数据，进行成分重组consituent、句型重组mood和风格重组style，以增强平行数据的多样性。


**如果您在您的工作中使用了该数据集，请引用以下论文**：

@inproceedings{DiRec,
    title = "基于多样性数据重组增强的藏汉神经机器翻译",
    
    author = "Jiayi, Xue  and
    
      Jinming, Chen  and
      
      Bo, Chen  and
      
      Wei, Bao  and
      
      Xiaobing, Zhao",
      
    booktitle = "Proceedings of the 24rd Chinese National Conference on Computational Linguistics (Volume 1: Main Conference)",
    
    month = jul,
    
    year = "2025",
    
    address = "Jinan, China",
    
    publisher = "Chinese Information Processing Society of China",
    
    language = "zho",
    
    abstract = "``高资源语言的神经机器翻译虽已取得显著进展，但低资源语言面临更严重的平行数据不足的问题。为此，提出一种面向藏汉神经机器翻译的多样性数据重组增强方法（DiRec）。该方法利用大语言模型的双向语言能力，对已有藏汉平行数据进行成分重组、句型重组和风格重组三种数据重组，经过滤质量自动筛选后得到多样性增强数据。在藏汉机器翻译的实验中，相较于基线模型，基于DiRec的模型的泛化能力指标提升4.83个百分点，BLEU提高0.55，chrF++提高0.20。最后分析了不同数据重组方式对翻译模型性能的影响。''"
}
