# 마크다운 markdown 작성법
마크다운(markdown)으로 README.md 파일 작성방법  

Markdown은 텍스트 기반의 마크업언어로 2004년 존그루버에 의해 만들어졌으며 Markdown은 웹 작성자를위한 텍스트-HTML 변환 도구입니다.
Markdown을 사용하면 읽기 쉽고 쓰기 쉬운 일반 텍스트 형식을 사용하여 작성한 다음 구조적으로 유효한 XHTML (또는 HTML)로 변환 할 수 있습니다. 
별도의 도구없이 Text로 저장하기 때문에 Git을 통한 버전관리가 가능 하고, 용량이 적어 보관이 용이 하다.

1.헤더Headers
-------------
This is an H2
-------------
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

2.BlockQuote
------------
블럭인용문자 >
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

3.목록
------
```
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째

순서없는 목록(글머리 기호: *, +, - 지원)
```
* 빨강
  + 녹색
    - 파랑
```
* 빨강
  + 녹색
    - 파랑   

작업 목록
```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

4.코드
------
문장 끝에서 2개의 공백 또는 하나의 탭으로 줄바꿈
```
This is a normal paragraph: 
  This is a code block.  
end code block.
```
This is a normal paragraph:  
  This is a code block.  
  end code block.

코드블럭1
```
* <pre><code>{code}</code></pre> 이용방식
* 코드블럭코드("```") 을 이용하는 방법
```
<pre><code>
```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```
</code></pre>

```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

표만들기 
```
| 왼쪽 정렬 | 가운데 정렬 | 오른쪽 정렬 |
|:--------|:--------:|--------:|
| 내용 11 | 내용 12 | 내용 13 |
| 내용 21 | 내용 22 | 내용 23 |
```
| 왼쪽 정렬 | 가운데 정렬 | 오른쪽 정렬 |
|:--------|:--------:|--------:|
| 내용 11 | 내용 12 | 내용 13 |
| 내용 21 | 내용 22 | 내용 23 |

5.수평선 <hr/>
--------------

```
* * *
***
*****
- - -
---------------------------------------
```
* * *
***
*****
- - -
---------------------------------------

6.텍스트 스타일
---------------
굵게, 기울임 꼴 또는 취소 선으로 강조 표시

문장 중간에 사용할 경우에는 **띄어쓰기** 를 사용

| Style | Syntax | Example |Output |
|:--------------|:----------------|:---------------------|:---------------------|
| Bold |``` ** ** or __ __ ```|``` **double asterisks** ```| **double asterisks** |
| Italic | ``` * * or _ _ ``` |``` *single asterisks* ```| *single asterisks* |
| Strikethrough | ``` ~~ ~~ ``` | ``` ~~cancelline~~ ``` | ~~cancelline~~|
| Bold & italic | ``` *** *** ``` |``` ***three asterisks*** ``` | ***three asterisks***|

7.링크
------

* 외부링크
```
사용문법: [Title](link)
적용예: [Google](https://google.com, "google link")
```
적용예: [Google](https://google.com, "google link")

* 자동연결
```
일반적인 URL 혹은 이메일주소인 경우 적절한 형식으로 링크를 형성한다.

* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>
```
외부링크: <http://example.com/>
이메일링크: <address@example.com>

8.이미지
--------
```      
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")

<img src="/path/to/img.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="Korea Flag"></img><br/>
<img src="/path/to/img.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="Korea Flag-s"></img>
```
<img src="https://kikiapps.netlify.app/image/tgg.png" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="Korea Flag"></img><br/>
<img src="https://kikiapps.netlify.app/image/tgg.png" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="Korea Flag-s"></img>

9.줄바꿈 & 문단 구분
---------------------
* 줄 바꿈을 하기 위해서는 문장 마지막에서 Space 2칸을 띄우고 Enter해야 한다. 
```
문장 마지막에서  Space 2칸을 띄어쓰기해야 한다.  (<-2 Space)
이렇게
```
문장 마지막에서  Space 2칸을 띄어쓰기하고 Enter해야 한다.  
이렇게
```
문단을 구분하려면

Enter를 두번 입력하면 됩니다.
```
문단을 구분하려면 

Enter를 두번 입력하면 됩니다.
