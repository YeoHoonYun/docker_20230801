"# docker_20230801"

### 로컬 임시 공간에 수정된 파일/정보를 넣는다.
git add .

### 위에 정보에 대해서 임시 폴더에 넣고, 레파지토리에 메시지 / 메타데이터를 넣어주는 부분
git commit -m "test"

### 레포지토리에 넣는 부분
git push

### 기존 브런치에 환경을 다시 재설정 하는 부분
git reset --hard

### 레포지토리에서 데이터를 가지고 오는 부분
git pull

### 브런치 환경 체크
git branch

### 브런치 환경 변환
git pull
git checkout developer

git checkout master