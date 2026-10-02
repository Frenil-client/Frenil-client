## 정휘현 - Unity Client Programmer

모바일 RPG의 UI와 핵심 콘텐츠 시스템을 설계하고 런칭부터 라이브 운영까지 맡아 온 Unity 클라이언트 프로그래머입니다.
경력 6년 9개월. 상점·결제·재화·캐릭터 스탯·던전 진입을 구현하고,
기획팀과 아트팀이 코드 수정 없이 콘텐츠를 다룰 수 있는 에디터 툴을 만들어 왔습니다.

- **독립 UPM 패키지 4종**: [UI 스택](https://github.com/Frenil-client/unity-ui-system), [MVVM](https://github.com/Frenil-client/unity-mvvm), [스탯](https://github.com/Frenil-client/unity-stat-system), [레드닷](https://github.com/Frenil-client/unity-reddot-system). MVVM·스탯·레드닷은 순수 C# 코어를 GitHub Actions가 매 푸시마다 빌드하고 헤드리스 테스트와 할당 벤치마크로 검증합니다.
- **[통합 데모](https://github.com/Frenil-client/unity-integration-demo)**: 스탯·MVVM·레드닷 패키지를 모바일 RPG 로비 하나로 연결했습니다. 패키지끼리 서로를 참조하지 않고, 연결 코드는 소비 프로젝트의 두 파일에 모았습니다.
- **[Spine FX 랩](https://github.com/Frenil-client/unity-spine-fx-lab)**: spineboy 300체를 화면 약 129 FPS로 그립니다. 화면 밖 인스턴스 컬링과 MaterialPropertyBlock으로 갱신 비용을 줄였고, 측정 조건과 분석은 [성능 분석 문서](https://github.com/Frenil-client/unity-spine-fx-lab/blob/main/Docs/analysis/multi-instance-perf.md)에 있습니다.
- **[URP NPR 셰이더 랩](https://github.com/Frenil-client/unity-urp-shader-lab)**: Shader Graph 없이 HLSL로 직접 작성한 셰이더 4종, 포스트 3종과 SDF 베이커 등 에디터 툴 6종.
- **[DefenceGame](https://github.com/Frenil-client/DefenceGame)**: 진행 중인 조합 디펜스 프로토타입. 명세·밸런스·맵·시뮬레이션 문서를 코드와 함께 두고, UnityEngine을 참조하지 않는 순수 C# 코어와 CSV 불변식 린터를 CI에서 실행합니다.

**전체 프로젝트와 상세 내용: [frenil-portfolio](https://github.com/Frenil-client/frenil-portfolio)**

`Unity` `C#` `URP` `HLSL` `Spine` `UGUI` `Addressables` `ScriptableObject` `MVVM`

📧 silsen@naver.com
