# ARCHIVIEW AX Studio — CAD 버전 변환기

Windows용 DWG 도면 AutoCAD 버전 일괄 변환 도구입니다.

## 사용 방법

1. [GitHub Releases](https://github.com/archiview2018/AX-Studio/releases)에서 `ArchiviewAXCadTool.exe`를 내려받아 실행합니다.
2. 변환할 AutoCAD 저장 버전 칩(`2018+`, `2013`, `2010`, `2007`, `2004`, 또는 `+` 확장으로 `2000`, `R14`)을 선택합니다.
3. 저장 폴더를 확인하거나 변경합니다.
4. DWG 도면 파일 또는 폴더를 대기열에 끌어다 놓거나 `+ 파일 추가`, `+ 폴더 통째로` 버튼을 이용합니다.
5. `변환 시작`을 누릅니다. 원본 도면은 덮어쓰지 않고 안전하게 보존됩니다.

## ODA 변환 엔진 안내

- DWG 변환에는 **ODA File Converter**가 필요합니다.
- 처음 실행 시 변환 엔진이 설치되어 있지 않으면 좌측 사이드바의 `ODA 공식 다운로드` 및 `설치 가이드 보기` 버튼으로 공식 설치 페이지를 안내합니다.
- 본 프로그램은 ODA File Converter 실행 파일을 포함하거나 재배포하지 않으며, 사용자가 공식 경로에서 직접 설치한 변환 엔진을 자동으로 탐색해 연결합니다.

## 버전 업데이트 및 의견 보내기

- 좌측 하단 `버전 업데이트 확인` 버튼으로 최신 공개 릴리스를 확인하고, SHA-256 무결성 검증 후 자동 업데이트할 수 있습니다.
- 실행 파일명은 버전이 변경되어도 항상 `ArchiviewAXCadTool.exe`로 유지되며, 버전은 앱 내부 표시와 GitHub Release 태그로 구분합니다.
- `필요한거 요청하기` 버튼을 누르면 기본 메일 앱에 버그 제보·기능 아이디어 양식이 열립니다.

## 요구사항

- Windows 10 / 11 (x64) 및 .NET Framework 4.x
- 앱 설정 저장 위치: `%APPDATA%\ArchiviewAXCadTool`
