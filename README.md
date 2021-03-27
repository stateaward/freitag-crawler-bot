# Freitag-Crawling-Bot

---

## 설치 순서
1. `pip install -r requirements.txt` 로 필요한 환경 설정
2. 만약 크롬드라이버가 설치 안되었다면, 설치하기


## Error
*에러*

> `[Errno 2] No such file or directory: './chromedriver'`

 1. 크롬드라이버가 설치되어 있는지 확인한다.

> 방법1) 자신의 크롬 버전과 동일한 드라이버 다운받기
>   > 1. 자신의 구글 버젼을 확인하기 (chrome://version/)
>   > 2. 웹드라이브 페이지에서 본인의 버전에 맞게 설치하기 [링크](https://sites.google.com/a/chromium.org/chromedriver/downloads)
>
> 방법2) MAC HOMEBREW 이용해서 다운받기
>   > - `brew cask install chromedriver`로 실시하기
>   >
>   > `Error: Unknown command: cask` 만약 cask가 설치되어 있는데도, 위와 같은 에러가 발생한다면.
>   > - `brew install --cask chromedriver` 로 설치하기

 2. 본인의 크롬 드라이브가 경로에 맞는지 확인한다. `/usr/local/bin/chromedriver`