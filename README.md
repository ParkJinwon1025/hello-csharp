# hello-csharp
hello-csharp

# 목차

1. [프로젝트 생성 방법](#-1.-프로젝트-생성-방법)

2. [프로젝트 실행 방법](#-2.-프로젝트-실행-방법)

3. [부가 정보](#-3.-부가-정보)

## 1. 프로젝트 생성 방법

1. `VS Code` 실행

2. Ctrl + Shift + P 

3. `.Net: New Project` 클릭

4. `Console App` 클릭

5. 계속 Enter

---

## 2. 프로젝트 실행 방법

1. 디렉토리 이동
```
cd hello-csharp
```

2. `VS Code` 실행
```
code .
```

3. `.\HelloCSharp\Program.cs` 선택

4. 우측 상단의 화살표 클릭

## 3. 부가 정보 
1. 하나의 폴더당 `.sln`은 보통 한 개만 만들어진다. 
2. 명령어로 sln에서 프로젝트를 추가 및 제거할 수 있음.
```bash
# 추가
dotnet sln add hello\hello.csproj

# 제거
dotnet sln remove hello\hello.csproj
```
3. `.sln`과 .`slnx`는 여러 csproj를 묶어 관리하는 파일로 역할은 동일하고 파일 형식만 다르다.
4. `csproj`파일은 프로젝트의 본체로 C# 프로젝트의 빌드 방법, 패키지 정보 등이 들어 있다.
5.  `Console App`은 콘솔 창에서 실행되는 프로그램을 의미한다.