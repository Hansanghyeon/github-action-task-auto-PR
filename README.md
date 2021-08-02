Github을 메인으로 사용하면서 Branch 전략을

- main
- develop
- Hansanghyeon/issue{0-9}

위와 같은 방식으로 작성한다.
내가 작업하는 저장소는 포크가 기본이라서 PR을 만들때 포크를 받아온 저장소가 자동적으로 만들어지는 것이 너무 불편했다.
고민을 해보다가 URL을 자동으로만드는 alfred workflow를 만들까? 처음 생각했는데
feature 브랜치를 만드는 것이 일상적이라 이 브랜치를 토대로 PR을 자동으로 만드는 것이 좋다 생각했다.

## Feature

- [ ] 해당 PR이있을 경우 jobs를 캔슬하는 것 if문으로
