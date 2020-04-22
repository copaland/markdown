# 마크다운 markdown 작성법

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
    
4.코드
------
4개의 공백 또는 하나의 탭으로 들여쓰기
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

6.강조
------
문장 중간에 사용할 경우에는 **띄어쓰기** 를 사용
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
```
*single asterisks*   
_single underscores_   
**double asterisks**   
__double underscores__   
~~cancelline~~   

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
* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>

* 참조링크
```
[link keyword][id]
[id]: URL "Optional Title here"
// code
link [Google][googlelink]
[googlelink]: https://google.com "Go google"
```  
[link Google] https://google.com "Go google"   

8.이미지
--------
```      
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
<img src="/path/to/img.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="/path/to/img.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>
```
<img src="https://kikiapps.netlify.app/image/tgg.png" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="Korea Flag"></img><br/>
<img src="https://kikiapps.netlify.app/image/tgg.png" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="Korea Flag"></img>

9.줄바꿈
--------
* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다. 
```
문장 마지막에서 3칸이상을 띄어쓰기해야 한다.    \\이렇게
```
문장 마지막에서 3칸이상을 띄어쓰기해야 한다.    \\이렇게
