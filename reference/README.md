## Scalable, multimodal profiling of chromatin accessibility, gene expression and protein levels in single cells
Peter Smibert: CITE-seq and ECCITE-seq
### Research background
1. 单细胞测序，尤其是scATAC-seq和scRNA-seq已经很成熟，并且被广泛应用在科研领域
2. 多模态的单细胞测序分析，例如：ATAC联合RNA表达，RNA联合蛋白，也都已有成熟的商业化的方案。但之前还没有ATAC-RNA-蛋白，三模态结合的单细胞测序方案。
3. 作者在本文中，介绍了他的团队新开发“ASAP-seq”方法。这个方法可以同时测“ATAC-RNA-蛋白”三个模态，而且还可以进一步拓展，以测到细胞内的蛋白，细胞表面蛋白，线粒体DNA的基因型，CRISPR干扰中用的sgRNA，这些更多纬度的信息。
### Experiment
**1. 开发并验证ASAP-seq方法**
先用带核算链标签的抗体panel，与被检测样本的细胞进行孵育， 孵育过程当中，抗体会和细胞上的抗原进行结合。接下来把细胞进行固定和通透化。通透化之后用带了核酸标签接头的Tn5的转座酶与被固定的细胞进行反应。反应的结果就是Tn5转座酶上面带的核酸标签，就会链接到染色体的DNA链开放区的位置。然后，用一个桥接的寡核苷酸连到抗体的标签链上。接下来进行10X的单细胞化，再建库测序。
**2. ASAP-seq是一个模块化的工具**
检验这个方法与其他方法的兼容性和一致性
UBI和UMI的比较
TSB (UBI)
TSA (UMI)



   
3. ASAP-seq揭示了细胞的状态，以及骨髓中的细胞系
4. 细胞分化期间的表面蛋白动态
5. ASAP-seq和CITE-seq揭示了三种调节
6. DOGMA-seq让同时测细胞的4中模态成为可能
7. 在原始的T细胞中复用CRISPR扰动
8. ASAP-seq让检测细胞内的蛋白成为可能