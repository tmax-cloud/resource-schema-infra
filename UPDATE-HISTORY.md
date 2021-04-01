## UPDATE HISTORY for json-schema generated files

- [Pod] deprecated된 serviceAccount 필드 제거 - IMS #256034
- [HPA] 기존 v2beta1에서 v2beta2로 변경
- [Pod] "io.k8s.api.core.v1.Container" definition에서 image 필드를 required에 추가
- [Pod] "io.k8s.api.core.v1.ResourceRequirements" 에 cpu, memory를 properties로 추가 (테스트 필요)