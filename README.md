## 정휘현 - Unity Client Programmer

모바일 RPG의 UI와 핵심 콘텐츠 시스템을 설계하고 런칭부터 라이브 운영까지 맡아 온 Unity 클라이언트 프로그래머입니다.
경력 6년 9개월. 상점, 결제, 재화, 캐릭터 스탯, 던전 진입을 구현하고,
기획팀과 아트팀이 코드 수정 없이 콘텐츠를 다룰 수 있는 에디터 툴을 만들어 왔습니다.

#### 대표 작업

- **[Aim Combat Slice](https://github.com/Frenil-client/unity-aim-combat-slice)**: 승리의 여신: 니케의 전투를 레퍼런스로 만든 조준 사격 전투 프로토타입입니다. 무기 3종, 데이터로 조합하는 스킬과 단계형 버스트, 보스 부위 파괴와 타격감을 넣었고, 피해 계산은 Unity 비의존 Core에서 고정소수점과 결정적 난수로 처리합니다. Jenkins로 만든 Windows, Android 빌드를 저장소에서 바로 받아 실행할 수 있습니다.

#### UI

- **UPM 패키지 3종**: [UI 스택](https://github.com/Frenil-client/unity-ui-system), [MVVM](https://github.com/Frenil-client/unity-mvvm), [레드닷](https://github.com/Frenil-client/unity-reddot-system). UI 스택은 DefenceGame과 Aim Combat Slice에서 쓰고, MVVM과 레드닷은 순수 C# 코어를 GitHub Actions가 매 푸시마다 빌드하고 헤드리스 테스트로 검증합니다.
- **[통합 데모](https://github.com/Frenil-client/unity-integration-demo)**: 스탯, MVVM, 레드닷 패키지를 모바일 RPG 로비 하나로 연결했습니다. 패키지끼리 서로를 참조하지 않고, 연결 코드는 소비 프로젝트의 두 파일에 모았습니다.

#### 그래픽스

- **[URP NPR 셰이더 랩](https://github.com/Frenil-client/unity-urp-shader-lab)**: Shader Graph 없이 HLSL로 직접 작성한 셰이더 4종, 포스트 3종과 SDF 베이커 등 에디터 툴 6종.
- **[Spine FX 랩](https://github.com/Frenil-client/unity-spine-fx-lab)**: spineboy 300체를 화면 약 129 FPS로 그립니다. 화면 밖 인스턴스 컬링과 MaterialPropertyBlock으로 갱신 비용을 줄였고, 측정 조건과 분석은 [성능 분석 문서](https://github.com/Frenil-client/unity-spine-fx-lab/blob/main/Docs/analysis/multi-instance-perf.md)에 있습니다.

#### 기타

- **[Lobby Flow](https://github.com/Frenil-client/unity-lobby-flow)**: Addressables 로컬/원격 그룹과 Unity CCD로 앱을 다시 설치하지 않고 시즌 콘텐츠를 v1에서 v2로 바꾸고, Jenkins가 플랫폼별 빌드, CCD 업로드, 공개 주소 검증까지 처리합니다. 비동기 미리보기의 늦은 결과 반환과 리소스 수명은 PlayMode 테스트와 30회 왕복 기록으로 확인했습니다.
- **[스탯](https://github.com/Frenil-client/unity-stat-system)**: long 고정소수점 저장과 모디파이어 분리, 최종값 캐싱을 갖춘 UPM 패키지입니다. 순수 C# 코어를 GitHub Actions에서 헤드리스 테스트와 할당 벤치마크로 검증합니다.

#### 게임 프로토타입

- **[DefenceGame](https://github.com/Frenil-client/DefenceGame)**: 진행 중인 조합 디펜스 프로토타입. 명세, 밸런스, 맵, 시뮬레이션 문서를 코드와 함께 두고, UnityEngine을 참조하지 않는 순수 C# 코어와 CSV 불변식 린터를 CI에서 실행합니다.

**전체 프로젝트와 상세 내용: [frenil-portfolio](https://github.com/Frenil-client/frenil-portfolio)**

`Unity` `C#` `UGUI` `MVVM` `URP` `HLSL` `Spine` `Addressables` `Unity CCD` `Jenkins` `ScriptableObject`

📧 silsen@naver.com
