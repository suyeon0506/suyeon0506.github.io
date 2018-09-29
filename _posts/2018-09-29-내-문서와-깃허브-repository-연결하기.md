---

layout: post
title: 내 문서와 깃허브 repository 연결하기
tags: [Coding, Github]

---

### 내가 매번 까먹어서 저장하는 방법

1. 깃허브 사이트에서 README와 함께 repository 생성
2. ~/Documents/git에서 git remote add origin "해당 repository 주소"
3. ~/Documents/git에서 git clone "해당 repository 주소"
4. 로컬 파일에서 해당 repository 폴더가 생성되면 cd를 통해 폴더로 들어간 후 필요한 파일들 옮겨줌
4. 외부 저장소를 clone 해서 옮겨올 때는 git submodule add "해당 외부 주소" (이 때 생성된 txt 파일은 경로를 설정해주므로 삭제 X)
5. git add . -> git commit -> git push