# Bioinfo1_free_project

This is a repository for _2022_1 Bioinformatics1_ project

* `Colab_Term_Project 1`
* `Colab_Term_Project 2`
* `Colab_Term_Project 3`

Han Byul Song <hansong@snu.ac.kr>


# Free Project:
(★)Fig S2A 재현해보기

<img width="400" alt="image" src="https://user-images.githubusercontent.com/89532424/170866740-f77ac00b-b293-4b23-a68e-774e1d3d69dd.png">


### 목표: ### 
Error가 많이 나오는 부분의 unique sequence들의 각각 개수를 세서 genome browser로 표현하고, 점수 트랙을 같이 표시합니다.

### 프로그램 언어: ###
Python (jupyter notebook)

### Workflow: ###
* Mirlet7d locus 위치 파악.
* Annotation 위치를 찾은 뒤 pileup 파일을 생성하여 각 position별로 base수를 세고 Shannon entropy를 계산.
* UCSC Genome Browser에 접속해서 bedgraph 파일을 업로드.
* 시각화

### 업데이트 ### (22/06/03)
* Mirlet7d 위치 파악 및 Bam filtering
* Shannon-Entropy 값 계산
* UCSC Genome Browser에 bedgraph 파일 업로드 및 시각화
* pdf 파일 업로드

### 참고자료: ###
* _Cho J, Chang H, Kwon SC, Kim B, Kim Y, Choe J, Ha M, Kim YK, Kim VN. LIN28A is a suppressor of ER-associated translation in embryonic stem cells. Cell. 2012 Nov 9;151(4):765-777. doi: 10.1016/j.cell.2012.10.019. Epub 2012 Oct 25. PMID: 23102813._
* _http://genome.ucsc.edu/goldenPath/help/bedgraph.html_

