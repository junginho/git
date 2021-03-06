# hello git

## git 명령어 요약

- clone: 원격 저장소 복사

- add: 스테이지 영역에 작업 파일 추가 

- commit: 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브)를 만들 수 있다. 

- push: 원격 저장소에 커밋을 업로드 한다.\

- branch

- checkout

- cherry-pick

- reset

- revert

- rebase

- merge

## 참고사이트

https://learngitbranching.js.org/?locale=ko

## 커밋 시 주의 사항

1. 반드시 한 번에 하느의 논리적 작업만을 커밋합니다.
2. 커밋 메시지를 잘 적어야 합니다.  

특히 커밋 메시지는 미래의 나와 다른 개발자들을 위해서 꼼꼼히 적어야 합니다. 

## 커밋 메시지 작성법

1. 첫 줄에 간단하지만 명확하게 내용을 씁니다. 
2. 한 줄 비우고 
3. 자세한 내용을 적습니다. 

## 파일의 내용 되돌리기

-checkout을 이용하면 아주 쉽게 마지막 커밋으로 되돌아 갈수 있다. 

-sourceTree의 `코드뭉치 버리기` 기능을 사용하면 변경사항을 되돌릴 수 있다. 

## 브랜치 변경하기

- 브랜치(branch): 기존의 내용을 유지한 체 새로운 내용을 추가하고 싶을 때 사용한다. 

- 머지(merge): 한 브랜치의 내용을 다른 브랜치에 반영

- 체크아웃(checkout): 특정 브랜치(혹은 커밋)으로 돌아가고 싶을 때 사용. 

- 소스트리 체크아웃: 브랜치 이름을 더블 클릭하는 것만으로 체크아웃 가능. 


## 병합이란?

- 하나의 브랜치를 현재의 브랜치와 합치는것을 병합(merge)라고 합니다.

- 현재 브랜치는 해드(head) 브랜치라고 합니다.

- 에를 들어 헤드 브랜치가 master이고 여기서 version2 브랜치를 병합하면 version2의 내용이 master에 반영되게 됩니다.

## 병합하기1

- 헤드 브랜치에 변경사항이 없고 

- 병합 대상 브랜치가 헤드로부터 시작된 경우

- 충동 없이 병합 가능 = Fast-forward





