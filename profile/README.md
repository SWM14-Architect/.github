# SW Maestro Architect Team

| [<img src="https://avatars.githubusercontent.com/u/45190017?v=4" width="150">](https://github.com/dasd412) | [<img src="https://avatars.githubusercontent.com/u/67100702?v=4" width="150">](https://github.com/westreed)| [<img src="https://avatars.githubusercontent.com/u/64861290?v=4" width="150">](https://github.com/ssfic3380) |
| :-----------------------------------: | :---------------------------------------: | :-------------------------------------: |
| 양영준 | 장세훈 | 허윤석 |

## Github Branch Strategy (GITHUB-FLOW)

![GITHUB-FLOW](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F70a1a%2FbtrAAZMILka%2FBwnRKBTeZX1UWI8sddApdK%2Fimg.png)<br>
> Github-flow 전략은 기능 개발, 버그 픽스 등 어떤 이유로든 새로운 브랜치를 생성하는 것으로 시작된다.  
단, 이때 체계적인 분류 없이 브랜치 하나에 의존하게 되기 때문에 브랜치 이름을 통해 의도를 명확하게 드러내는 것이 매우 중요하다.

1. master 브랜치는 항상 최신 상태며, stable 상태로 product에 배포되는 브랜치다. 이 브랜치에 대해서는 엄격한 role과 함께 사용한다.
2. 새로운 브랜치는 항상 master 브랜치에서 만든다.
3. Git-flow와는 다르게 feature 브랜치나 develop 브랜치가 존재하지 않는다.
4. 그렇지만, 새로운 기능을 추가하거나 버그를 해결하기 위한 브랜치 이름은 자세하게 어떤 일을 하고 있는지에 대해서 작성해주도록 하자.
5. 코드리뷰 이후 Merge 하기 전에, 테스트를 진행해야 한다.
