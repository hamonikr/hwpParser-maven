# hwpParser-maven
 
* 사용한 라이브러리나 문서 
	- Apache-POI 라이브러리 - 한글 파일의 하부 구조인 Microsoft Compound File의 부분의 파싱.
	- 한글과컴퓨터에서 공개한  '한글 문서 파일 구조 5.0' 문서 ( http://www.hancom.com/etc/hwpDownload.do?gnb0=269&gnb1=271&gnb0=101&gnb1=140 )

* 이 라이브러리에서 할 수 있는 일.(kr.dogfoot.hwplib.test 패키지 참조)
	- 한글 파일을 읽어서 객체로 생성 (TestReadingHWPFile 참고)
	- 만들어진 객체를 파일로 저장 (TestReWritingHWPFile 참고)
	- 한글 파일에서 텍스트 추출(TestExtractingText 참고)
	- 특정 필드의 텍스트 추출  (TestGettingClickHereFieldText 참고)
	- 특정 필드의 텍스트 설정 (TestSetClickHereFieldText 참고)
	- 조건에 맞는 컨트롤 찾기 (TestFindControl 참고)
	- 다른 파일의 내용(문단)을 추가하기 (TestParagraphAdder 참고)
	- 표의 셀 병합하기 (TestMergingCell 참고)
	- 기타  설정 : 페이지 크기 변경 (TestChangePaperSize 참고), 이미지 주가(TestInsertImage 참고), 폰트 크기, 밑줄 등의  글자모양 설정(TestMakingCharShape 참고), 표 컨트롤 생성 (TestMakingTable 참고)...

이 프로젝트의 출처는  https://github.com/neolord0/hwplib 입니다.

2019.07.24
=========================================================================================
* maven 프로젝트로 변환
