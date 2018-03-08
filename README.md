# Graduation Design 18-1

### 업로드 방법
* 졸업설계를 수행한 날짜 + 제목으로 폴더를 만든 후, 해당 폴더에 자료를 업로드하세요.
* 가능하면 각 수행한 폴더 내에 README.md 파일을 소신껏 꾸며서 추가해두시기 바랍니다.
    - 해당 폴더, 즉 해당 날짜에 수행한 졸업설계 내용 및 코멘트등을 정리하는 문서를 README.md로 작성하세요.
    - MarkDown 문법을 확인해보세요.
* 본 repository의 folder tree는 다음과 같이 구성될 수 있습니다.(예시)

```
 .
├── Professor
│   └── XXX(folder)
│          └── some files
│          └── README.md
├── Team-1
│   └── XXXX-XX-XX-주제탐색(folder)
│          └── some files
│          └── README.md
├── Team-2
│   └── XXXX-XX-XX-주제탐색(folder)
│          └── some files
│          └── README.md
├── LICENSE.md
└── README.md
```


create a new repository on the command line

```
git clone https://github.com/AInCT/Graduation-Design-18-1.git
git init
git add *
git commit -m "your commit message"
git remote add origin https://github.com/AInCT/Graduation-Design-18-1.git
git pull origin master
git push -u origin master
```

push an existing repository from the command line

```
git remote add origin https://github.com/AInCT/Graduation-Design-18-1.git
git pull origin master
git push -u origin master
```