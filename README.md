# 5_CS_STUDY

<br>

<br>

> ### 참여인원

* :man_technologist: 김무종 

* :woman_technologist: 김혜림 
* :woman_technologist: 마주리 
* :woman_technologist: 장한나

<br>

<br>

<br>

> ### 커밋메세지

`<본인이름>:<발표 주제>`

<br>

<br>

<br>

> ### 사용방법

1. 원하는 디렉토리에서 `git clone`을 통해 `5_cs_study` 레포지토리를 본인의 로컬 PC로 가져갑니다.

   ```bash
   # git clone
   $ git clone https://github.com/joorii/5_cs_study.git
   ```

2. clone 받은 `5_cs_study`로 디렉토리를 이동합니다.

   ```bash
   # 5_cs_study로 이동
   $ cd 5_cs_study
   ```

3. 본인 이름의 `Branch`를 생성합니다.

   ```bash
   # <본인이름> 브랜치 생성 및 이동
   $ git swtich -c <본인이름>
   ```

4. 스터디 자료를 본인 이름의 `Branch`에 업로드합니다.

   ```bash
   # Markdown 문서를 본인의 브랜치에서 git에 업로드
   $ git add .
   $ git commit -m "< commit 내용 >"
   $ git push origin <본인이름>
   ```

5. `Pull requests`를 생성합니다.

   * `5_cs_study` 레포지토리(https://github.com/joorii/5_cs_study)에 들어와서 상단에 위치한 `Compare & pull requests` 버튼을 클릭합니다.
   * 만일 해당 버튼이 안나타날시에는, `pull requests` 메뉴 > `New pull request` 버튼을 클릭합니다.
   * `base:master <- compare:<본인이름>` 으로 설정 후 `request`의 제목 및 내용을 수정한 뒤 `Create pull request`을 눌러 `request`를 오픈해주세요.
   * 스터디가 끝난 후 모든 사람의 `request`가 모여지면 1주일에 1번씩 `Merge`할 예정입니다.

6. `Merge`가 완료되면 `git pull`을 통해 `master`의 버전과 본인의 `Branch`의 버전을 맞추어주세요.

   ```bash
   # git pull
   $ git pull origin master
   ```

7. 초기 설정이 완료되면 그 이후에는 4 ~ 6번의 과정을 반복하며 사용하면 됩니다.

<br>

<br>

<br>

> ### 참고사이트

* https://github.com/gyoogle/tech-interview-for-developer