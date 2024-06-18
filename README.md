# llm_finetuning
llama2-7b finetuning for summary


한양대학교 산업융합학부 정보공학전공 프로젝트 
================================

**프로젝트 : 한국어 뉴스 요약 특화 모델 파인 튜닝**

( 등록일 : 2024-06-12)

▷ 교 과 목 명 : 인공지능1 

▷ 담당교수님 : 정 철 현(inbass@hanyang.ac.kr)

▷ 수 업 년 도 : 2024

**참여 인원**

▶ 김지희(7092) wlgml2419@hanyang.ac.kr

▶ 서호림(5832) rh2103@hanyang.ac.kr

▶ 한태혁(4139) xogur2420@gmail.com


[Contribution guidelines for this project](http://devocean.sk.com/blog/techBoardDetail.do?ID=165703&boardType=techBlog)



**코드 설명**
1. Summary with Llama2 without fine-tuning.ipynb 
    - 라마2 불러와서 요약 결과 확인
    

2. Llama2 fine-tuning with naver-news dataset for summary.ipynb
    - 라마2 파인튜닝 데이터 : daekeun-ml/naver-news-summarization-ko 
    - 모델 : llama-2-7b-it-sum-ko_max_step=500


3. Llama2 fine-tuning with aihub dataset for summary.ipynb
    - 라마2 파인튜닝 데이터 : aihub 문서요약 텍스트 ([AI-Hub 데이터](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=97))
    - 모델 : llama-2-7b-it-sum-ko_max_step=500_aihub
    - 학습 과정에서 문제가 있는 것으로 보임 - 요약_성능 이상함(추후 업데이트 예정)


4. Summary service using crawling + finetuned Llama2 model.ipynb
    - 라마2 파인튜닝 모델로 크롤링한 뉴스기사 요약


※ 해당 프로젝트는 Llama2 7b를 이용한 파인튜닝으로 코드 실행 시 개인의 API Key 등록 필수
> [!NOTE]
>**필요 API Key**
> 
>＊ Huggingface API Key
> 
>＊ Naver Open API ID, Secret
