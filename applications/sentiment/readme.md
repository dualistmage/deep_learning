# Sentiment Analysis TF Example code 

Author : Sangkeun Jung (2017)

This repo contains sentiment analysis example codes. 

The purpose of this scripts is for educating how to write deep learning building blocks for natural language processing (not for introducing state-of-the-arts performance).

- 4 polarities
	: Positive, Negative, Neutral, Objective
- character based encoding 
- use supervisor pattern to deal with model saving & restoring
- data is filtered ( length < 128 )

Korean Sentiment Analysis data is from 

	- https://air.changwon.ac.kr/blog/2013/08/21/%ED%8A%B8%EB%A6%BD%EC%96%B4%EB%93%9C%EB%B0%94%EC%9D%B4%EC%A0%80-%ED%95%9C%EA%B5%AD%EC%96%B4-%EC%A0%95%EC%84%9C%EB%B6%84%EC%84%9D-%EC%BD%94%ED%8D%BC%EC%8A%A4-%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C/

	- You should cite following reference to use 
		- [English] Won-Sik Bae and Jeong-Won Cha, ?쏛utomatic Opinion Relations Extraction for Sentiment Analysis,??Journal of KIISE: Software and Applications, vol. 40, no. 5, pp. 473-481, 2013. (in Korean)

		- [Korean] 배원식, 차정원, “정서분석을 위한 의견관계 자동추출,” 한국정보과학회논문지: 소프트웨어 및 응용, 제40권, 제5호, pp. 473-481, 2013.
		
		
( Overall code structure and some codes are inspired by https://github.com/rafaljozefowicz/lm)
