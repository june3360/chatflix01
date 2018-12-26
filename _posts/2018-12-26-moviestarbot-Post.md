---
title: SSAFY Start Camp 챗봇 퀘스트
---
광주_2_허영, <https://github.com/heoyoung/moviestarbot>

# I.스펙(Spectification)

(1) 기타의 말 
* 키워드에 없는 명령어에 대해 메뉴 출력을 통한 키워드 검색을 유도

(2) 개봉예정작
* 검색일 기준으로 개봉우선순위의 영화를 리스트로 보여줌

(3) 평점
* CGV영화사 골든에그지수 95% 이상의 영화를 정렬 후 보여줌

(4) 영화추천
* CGV영화사 차트 Top10을 리스트로 보여줌

(5) 영화제목 검색
* 영화제목 검색시 해당영화의 CGV 골든에그 지수와 썸네일 이미지를 보여줌

(6) 영화배우 검색
* 영화배우 검색시 해당배우의 출연작을 리스트로 보여줌

(7) 영화감독 검색
* 영화감독 검색시 해당감독의 연출작 영화를 최근순으로 정렬하여 리스트로 보여주고 썸네일 이미지를 보여줌

# II.회고(Retrospective)

(1) 크롤링 과정에서의 어려움
* 영화 배급사의 html 태그 및 클래스나 ID파악에 어려움이 있었음
* 셀레니움으로 자료를 크롤링 하는 과정에 다소 시간이 걸림

(2) 메시지 출력에서의 어려움
* 이미지와 리스트자료를 함께 출력하는것에 어려움이 있었음

# III.보완 계획(Feedback)

(1) 이미지와 텍스트 구성 개선
* 이미지와 텍스트를 보다 가독성이 높게 끔 구성하여 출력하고자 함

(2) 폭넓은 자료 크롤링
* CGV 뿐만이 아닌 다른 영화배급사의 자료도 크롤링하고자 함

(3) 키워드 검색 확장
* 주 연령대, 매력지수, 장르 등의 다양한 키워드를 통한 검색기능을 추가하고자 