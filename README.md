# 이어폰 관련 설문조사 및 통계 사이트

<img src="https://github.com/keamy-eun/html_ToyTermProject/blob/master/docs/img/img.JPG?raw=true">

# 1차 프로잭트 내용: HTML/CSS 활용 UI구현

#### 프로젝트 기간

#### 2022.11.10 ~ 2022.11.11

<hr>
HTML_ToyTermProject

- [Github Pages](https://keamy-eun.github.io/html_ToyTermProject/html/main.html)
- [Video](https://youtu.be/czO1pB3gt1c)

<hr>

## 프로잭트 구성

- [화면설계](https://docs.google.com/presentation/d/1MT4p00oV3MBD5iE9hGsuAbLri1B2ZzOC4RzTV5BKOyU/edit#slide=id.g188a90b9cce_1_3)

## 업무분담

- 메인, 로그인, 회원가입, NAV BAR : 이찬우
  - [main](./docs/html/main.html)
  - [login](./docs/html/login.html)
  - [signup](./docs/html/signUp.html)
- 설문, 통계메인, 통계메뉴1~2, ASIDE BAR: 은원기
  - [survey](./docs/html/survey.html)
  - [statics](./docs/html/statics.html)
  - [statics_menu1](./docs/html/statics_menu1.html)
  - [statics_menu2](./docs/html/statics_menu2.html)

<hr>

# 2차 프로잭트 내용: Bootstrap 활용 UI구현

#### 프로젝트 기간

#### 2022.12.08 ~ 2022.12.09

<hr>
HTML_ToyTermProject

- [Github Pages](https://keamy-eun.github.io/html_ToyTermProject/Bootstrap/main.html)
- [Video](https://youtu.be/b0OGmnU35vQ)

<hr>

## 업무분담

- 메인, 로그인, 회원가입: 이찬우
  - [main](./docs/Bootstrap/main.html)
  - [login](./docs/Bootstrap/login.html)
  - [signup](./docs/Bootstrap/signUp.html)
- 설문, 통계메인, 통계메뉴1~2: 은원기
  - [survey](./docs/Bootstrap/survey.html)
  - [statics](./docs/Bootstrap/statics.html)
  - [statics_menu1](./docs/Bootstrap/statics_menu1.html)
  - [statics_menu2](./docs/Bootstrap/statics_menu2.html)

<hr>

#### 주요코드 선정 / 은원기

#### row & col을 사용하여 정렬이 간편하고 table-striped-columns으로 table 요소들을 구별지을 수 있다.

```
      <div class="col-5">
        <table class="table table-bordered table-striped-columns">
          <thead>
            <tr>
              <th colspan="2">2021 업체별 이어폰 시장 점유율</th>
            </tr>

            ...

          </thead>
        </table>
      </div>
```

#### 주요코드 선정 / 이찬우

#### 로그인을 실행하는 주요 화면

```
<div class="card-body">
          <form action="./login.html" method="get">
            <!-- login menu title -->
            <div class="text-center fs-1">LOGIN</div>
            <!-- input group -->
            <div class="input-group d-flex flex-column">
              <label for="id" class="form-label"
                >아이디
                <input
                  name="memberId"
                  id="id"
                  type="text"
                  class="form-control"
                />
              </label>
              <label for="pw" class="form-label"
                >비밀번호
                <input
                  name="memberPW"
                  id="pw"
                  type="text"
                  class="form-control"
                />
              </label>
              <label for="">
                <button type="submit" class="btn btn-primary w-100 mt-3">
                  Sign in
                </button>
              </label>
            </div>
          </form>
        </div>
```
