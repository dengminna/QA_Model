# Intro of QA-Model

`NLPCC_CNN`: 2017 `NLPCC` DBQA ������3rd(`MRR=0.685011`)

`CCIR_CNN`: 2017 `CCIR` �ѹ��ʴ����������9th(`NDCG@3=0.7006 NDCG@5=0.7398`)

`DocumentClassification`: ����AI1000�ı����� & CNEWS����

`MPCNN-sentence-similarity`: Sentence Similarity Based on Attention

# Run
`NLPCC_CNN`:

    Step1: corpus/nlpcc16-dbqa-data/train��readme

    Step2: corpus/nlpcc16-dbqa-data/test��readme

    Step3: cnn/theano/��readme


    
<br>
Tips��Ŀǰ�ڴ���train��test����ʱ���õķִ���cnn.theano.util.word_segment.segment_word_filter_pos,
�����Ҫ���Ŀ���corpus/nlpcc16-dbqa-data/train��corpus/nlpcc16-dbqa-data/test�еĽű������滻����
(���滻Ϊcnn.theano.util.word_segment.segment_word)