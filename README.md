# 전기 전력 계산기

이 저장소는 **전압·전류·저항**을 이용해 전력을 계산해 주는 간단한 웹 애플리케이션입니다.  
`index.html` 하나만으로 동작하므로 GitHub Pages에 바로 배포할 수 있습니다.

## 사용 방법

1. **새 GitHub 저장소**를 만듭니다.  
2. 이 ZIP 파일의 내용을 저장소 루트에 업로드하거나, 로컬에서 `git add . && git commit -m "Init"` 후 `git push` 합니다.  
3. 저장소의 **Settings ▸ Pages**(혹은 **Deployments ▸ Pages**) 메뉴로 이동해  
   - **Build and deployment source**에서 **Deploy from a branch**를 선택  
   - 브랜치: `main` (또는 기본 브랜치)  
   - 폴더: `/ (root)`를 지정해 **Save** 합니다.  
4. 잠시 뒤 `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` 주소에서 계산기를 확인할 수 있습니다.

## 파일 구성
| 파일 | 설명 |
|------|------|
| `index.html` | 계산기 애플리케이션 |
| `README.md` | 저장소 및 배포 가이드 |

---

> ⚡ 계산 공식  
> - **P = V × I**  
> - **P = I² × R**  
> - **P = V² / R**
