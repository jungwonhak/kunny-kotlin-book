# Simple Github
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

차세대 안드로이드 개발자를 위한: 커니의 코틀린 도서의 2부에서 다루는 **Simple Github** 예제 애플리케이션 저장소입니다.

## 코드 변경사항 안내

오류 수정 혹은 업데이트로 인해 코드가 변경될 수 있습니다. 전체 변경 내역은 [CHANGELOG](https://github.com/kunny/kunny-kotlin-book/tree/master/CHANGELOG.md) 문서를 참조하세요.

## 브랜치 목록

각 장에서 완성하게 되는 코드는 주제별로 구분되어 있는 브랜치로 확인할 수 있습니다.

각 브랜치는 직전의 브랜치를 기반으로 작성됩니다. (예: ``arch-components-lifecycle`` 브랜치에는 직전 브랜치인 ``rxjava-rxbinding``을 기반으로 구현되었으므로, ``RxJava`` 와 ``RxBinding``이 모두 적용되어 있는 상태입니다)

| 브랜치 | 언어 |  장 | 제목 | 책에서 다루는 내용 |
| --- | -- | --- | --- | --- |
| [java](https://github.com/kunny/kunny-kotlin-book/tree/java) | Java | 10 | Simple Github 프로젝트 소개 | 자바로 작성한 Simple Github 예제 프로젝트 설명 |
| [kotlin-step-1](https://github.com/kunny/kunny-kotlin-book/tree/kotlin-step-1) | Java + Kotlin | 11 | 코틀린 변환 1단계: 컨버터로 자바 코드 변환하기 | Simple Github 예제 프로젝트에 코틀린 개발환경 설정, 컨버터를 사용하여 UI 코드를 코틀린으로 변환하는 절차 |
| [kotlin-step-2](https://github.com/kunny/kunny-kotlin-book/tree/kotlin-step-2) | Kotlin | 12 | 코틀린 변환 2단계: 코틀린 다운 코드로 다듬기 | 11장에서 작업했던 코드에서 남은 자바 코드를 컨버터를 사용하여 코틀린으로 변환 후, 변환된 코드를 코틀린 답게 다듬는 방법 |
| [rxjava](https://github.com/kunny/kunny-kotlin-book/tree/rxjava) | Kotlin | 13 | 프로젝트 개선 1단계: RxJava 적용하기 | [RxJava](https://github.com/ReactiveX/RxJava)를 사용하여 이벤트를 기반으로 애플리케이션 동작을 처리하는 방법 |
| [rxjava-rxbinding](https://github.com/kunny/kunny-kotlin-book/tree/rxjava-rxbinding) | Kotlin | 13 | 프로젝트 개선 1단계: RxJava 적용하기 | [RxBinding](https://github.com/JakeWharton/RxBinding)으로 UI 이벤트를 RxJava로 처리하는 방법 |
| [arch-components-lifecycle](https://github.com/kunny/kunny-kotlin-book/tree/arch-components-lifecycle) | Kotlin | 14 | 프로젝트 개선 2단계: 안드로이드 아키텍처 컴포넌트 적용하기 | [Lifecycle](https://developer.android.com/topic/libraries/architecture/lifecycle.html)을 사용하여 액티비티 생명주기에 따른 동작 처리하기 |
| [arch-components-room](https://github.com/kunny/kunny-kotlin-book/tree/arch-components-room) | Kotlin | 14 | 프로젝트 개선 2단계: 안드로이드 아키텍처 컴포넌트 적용하기 | [Room](https://developer.android.com/topic/libraries/architecture/room.html)으로 손쉽게 SQLite 데이터베이스를 다루기 |
| [arch-components-viewmodel](https://github.com/kunny/kunny-kotlin-book/tree/arch-components-viewmodel) | Kotlin | 14 | 프로젝트 개선 2단계: 안드로이드 아키텍처 컴포넌트 적용하기 | [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel.html)을 사용하여 액티비티 상태 보존하기 |
| [dagger-step-1](https://github.com/kunny/kunny-kotlin-book/tree/dagger-step-1) | Kotlin | 15 | 프로젝트 개선 3단계: 대거로 의존성 주입 처리하기 | [Dagger](https://google.github.io/dagger/)를 사용하여 API 및 데이터베이스 객체를 의존성 주입으로 처리하기 |
| [dagger-step-2](https://github.com/kunny/kunny-kotlin-book/tree/dagger-step-2) | Kotlin | 15 | 프로젝트 개선 3단계: 대거로 의존성 주입 처리하기 | 각 액티비티의 ``ViewModel`` 및 리사이클러뷰 어댑터 객체를 의존성 주입으로 처리하기 |

## 빌드 환경

예제 애플리케이션 빌드에 사용하는 환경은 다음과 같습니다.

| 항목 | 버전 |
| --- | --- |
| Android Gradle Plugin | `3.0.0` |
| Build Tools | `27.0.1` |
| Minimum SDK | `15` |
| Compile SDK | `27` |
| Target SDK | `27` |

## 사용하는 라이브러리 및 버전

예제 애플리케이션에서 사용하는 라이브러리 및 버전은 다음과 같습니다.

| 이름 | 라이선스 | 버전 |
| --- | --- | --- |
| [Anko](https://github.com/Kotlin/anko) | [Apache License 2.0](https://github.com/Kotlin/anko/blob/master/LICENSE) | `0.10.2` |
| [Android Architecture Components](https://developer.android.com/topic/libraries/architecture/index.html) | Apache License 2.0 | `1.0.0` |
| [Android Support Library](https://developer.android.com/topic/libraries/support-library/index.html) | Apache License 2.0  | `27.0.1` |
| [Dagger](https://google.github.io/dagger/) | [Apache License 2.0](https://github.com/google/dagger/blob/master/LICENSE.txt) | `2.12` |
| [Glide](https://github.com/bumptech/glide) | [LICENSE](https://github.com/bumptech/glide/blob/master/LICENSE) | `4.1.1` |
| [Gson](https://github.com/google/gson) | [Apache License 2.0](https://github.com/google/gson/blob/master/LICENSE) | `2.7` |
| [Kotlin](https://github.com/JetBrains/kotlin) | [LICENSE](https://github.com/JetBrains/kotlin/tree/master/license) | `1.1.60` |
| [OkHttp](http://square.github.io/okhttp/) | [Apache License 2.0](https://github.com/square/okhttp/blob/master/LICENSE.txt) | `3.8.1` |
| [Retrofit](http://square.github.io/retrofit/) | [Apache License 2.0](https://github.com/square/retrofit/blob/master/LICENSE.txt) | `2.3.0` |
| [RxAndroid](https://github.com/ReactiveX/RxAndroid) | [Apache License 2.0](https://github.com/ReactiveX/RxAndroid/blob/2.x/LICENSE) |  `2.0.1` |
| [RxBinding](https://github.com/JakeWharton/RxBinding) | [Apache License 2.0](https://github.com/JakeWharton/RxBinding/blob/master/LICENSE.txt) | `2.0.0` |
| [RxJava](https://github.com/ReactiveX/RxJava) | [Apache License 2.0](https://github.com/ReactiveX/RxJava/blob/2.x/LICENSE) | `2.1.3` |

## 라이선스

이 저장소를 통해 제공되는 내용은 [저작자표시-비영리-동일조건변경허락 4.0 국제](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ko) 라이선스에 따라 제공됩니다. 라이센스에 대한 상세한 설명은 위의 링크 및 [전문](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)을 참조하세요.

다음은 이 저장소에서 제공되는 코드를 **사용할 수 없는** 대표적인 사례를 보여줍니다.

* 이 저장소에서 제공되는 코드의 일부 혹은 전부를 활용하여 **영리 목적**의 강의, 출판물, 컨설팅 등에 사용하는 경우
* 이 저장소에서 제공되는 코드의 일부 혹은 전부를 활용하여 **광고를 통해 게재자가 수익을 얻을 수 있는 지면** 혹은 **게재에 따른 보상으로 고료 혹은 그에 상응하는 보상을 받는 매체**에 게재하는 경우

다음은 이 저장소에서 제공되는 코드를 **사용할 수 있는** 대표적인 사례를 보여줍니다.

* 이 저장소에서 제공되는 코드의 일부 혹은 전부를 활용하여 **비영리 목적**의 강의, 출판물, 컨설팅 등에 활용하고, 이 저장소 및 해당 코드의 링크와 라이선스 링크를 제공하는 경우
* 이 저장소에서 제공되는 코드의 일부 혹은 전부를 활용하여 **광고가 없는 지면** 혹은 **게재에 따른 보상으로 보상을 지급하지 않는 매체**에 게재하는 경우

위에서 제시한 사례들(이 저장소에서 제공되는 코드를 사용할 수 있는 사례와 사용할 수 없는 사례)은 가능한 사례 중 일부일 뿐입니다. 따라서 앞에서 소개한 사례 외에도 라이선스에 따라 저작물 사용이 제한되는 경우가 있을 수 있습니다.

라이선스와 관련하여 추가 문의가 필요하신 분은 jyte82@gmail.com 으로 개별 연락 부탁드립니다.
