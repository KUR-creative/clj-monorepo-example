# uix front + back + share project template
shared deps duplication?
- https://ask.clojure.org/index.php/9849/teams-common-dependencies-tooling-across-multiple-projects
- https://clojure.atlassian.net/jira/software/c/projects/TDEPS/issues/TDEPS-174
- 일단 그냥 손으로 sync할 것.
- 나중에 share에 deps.edn를 두고, 스크립트로 b,f를 각각 생성하는 수 밖에..

share는 일종의 라이브러리가 된다. util도 똑같이 집어 넣으면 된다. 정말로 프로젝트와 독립적인 lib이라면 추후 git이나 clojars로 배포도 가능.
