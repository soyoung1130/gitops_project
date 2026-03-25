# GitOps Project for OpenShift Argo CD

이 프로젝트는 test_project(앱) 배포를 위한 Argo CD Application 리소스를 포함합니다.

- argocd-application.yaml: Argo CD에서 사용할 Application CRD 예시
- repoURL, path, namespace 등은 실제 환경에 맞게 수정하세요.

## 적용 방법

1. Argo CD가 설치된 OpenShift 클러스터에서 아래 명령어로 적용:

   oc apply -f argocd-application.yaml

2. Argo CD UI에서 동기화(Sync)하여 배포 상태를 확인할 수 있습니다.
