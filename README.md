# 영국 왕립 통계 학회(Royal Statistical Society) 발행 '데이터 시각화 모범 사례'

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10600718.svg)](https://doi.org/10.5281/zenodo.10600718)


이 GitHub 리포지토리는 <https://royal-statistical-society.github.io/datavisguide/> 웹사이트의 모든 소스 파일과 코드를 포함하고 있습니다. 사이트와 콘텐츠는 개발 중이며, 편집자들은 피드백과 기여를 환영합니다.

## 개발 환경 설정 (Pixi)

이 프로젝트는 패키지 관리를 위해 [pixi](https://prefix.dev/)를 사용합니다. Pixi를 설치한 후 다음 명령어를 사용하여 환경을 설정하고 프로젝트를 실행할 수 있습니다.

```bash
# pixi 설치 (이미 설치된 경우 생략)
curl -fsSL https://pixi.sh/install.sh | bash

# 의존성 설치 및 쉘 실행
pixi shell

# 웹사이트 미리보기
pixi run quarto preview
```

## 제안하거나 질문하기

리포지토리의 [생각 공유(Discussions)](https://github.com/royal-statistical-society/datavisguide/discussions) 섹션에서 토론을 시작해 주세요.

## 버그나 오류를 발견했다면

다음 중 하나를 수행해 주세요:

1.  리포지토리의 [문제(Issues)](https://github.com/royal-statistical-society/datavisguide/issues) 섹션에 이슈를 제기합니다.
2.  이 리포지토리를 포크(Fork)하고, 관련 파일을 수정한 후, 이 리포지토리의 `main` 브랜치에 풀 리퀘스트(Pull Request)를 보냅니다.

## 가이드에 새로운 기능이나 섹션을 추가하고 싶다면

1.  리포지토리의 [문제(Issues)](https://github.com/royal-statistical-society/datavisguide/issues) 섹션에 이슈를 제기하고, 'enhancement' 태그를 단 후 제안하는 기여 내용을 설명합니다.
2.  이 리포지토리를 포크하고, 예를 들어 `my-new-feature-or-section`과 같은 이름으로 새 브랜치를 만듭니다.
3.  브랜치에 콘텐츠, 코드 및 파일을 추가합니다.
4.  이 리포지토리의 `main` 브랜치에 풀 리퀘스트를 보냅니다.

새로운 기능이나 섹션에 대한 제안은 다음 편집팀이 검토합니다:

-   Andreas Krause

-   Nicola Rennie

-   Anna Britten

검토자는 풀 리퀘스트 병합에 동의하기 전에 기여자에게 피드백이나 제안을 제공할 수 있습니다. 편집팀은 풀 리퀘스트 병합을 거부할 권리가 있으며, 편집팀의 결정이 최종적입니다.

이 웹사이트와 리포지토리의 사용 및 모든 기여는 [행동 강령](CODE_OF_CONDUCT.md)의 적용을 받습니다.

편집팀이 작성하고 이 웹사이트 및 리포지토리에 게시된 콘텐츠는 [Creative Commons Attribution 4.0 (CC BY 4.0) International 라이선스](http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1) 하에 배포됩니다. 이는 원저작자를 표시하는 한, 어떤 목적으로든 사용 및 수정이 가능함을 의미합니다. 이 가이드에 기여함으로써 기여자들은 자신의 작업물을 동일한 조건으로 라이선스하는 것에 동의하게 됩니다.

이 사이트는 [Quarto](https://quarto.org/)로 구축되었습니다. Quarto 사용을 시작하려면 <https://quarto.org/docs/get-started/>를 방문하세요.
