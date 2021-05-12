
2018年底投ACL的一篇关于sentence-level sentiment classification论文。一般来讲，为了训练sentence-level sentiment的classifier，我们需要在句子层面上进行情感标注，这样非常费时费力。这篇论文提出只需要标注一大段文章的情感极性，然后使用一种attention机制，可以得到句子层面的sentiment。 这个方法在今天（2021）看来很平常，但是在2017年是非常具有创新性的。 评审结果是1票赞同，1票反对，反对意见是实验数据没有使用标准的公开数据。当时忙于毕业，对这个反对意见没有时间去处理了，最后没有发表

# Demo for the submission 'Attention-with-logits: an End-to-end Weakly Supervised Approach for Sentence-level Sentiment Classification' 

To run the notebook file, it is better to import it into an enviroment with a gpu. Becuse of the storage limit, the data used in the accopmying paper cannot be included. Instead, we chose to read the data from IBM's cloud service.
Furthermore, for some procedural reasons, only a small part of the data described in the accompying paper is used in this file. The compelete datasets will be released soon. 

Readers can also supply their own data to run the file. We observed that it is easy to reproduce the advantage of the proposed approach reported in the paper on a new dataset other than the ones described in the paper. 


