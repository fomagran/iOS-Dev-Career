# iOS-Dev-Career

![apple_ios_developer](/images/apple_ios_developer.jpg)

- iOS 개발 면접 질문을 정리하는 곳입니다.

#### ㅁ 질문, 답변 작성 방법

> - 질문의 경우 아래 해당되는 카테고리의 표에 추가해 주세요.
> - 답변의 경우 [답변 템플릿](Answer_Template.md)의 형식으로 작성해 `/answers` 폴더에 추가해 주세요.
> - 이미지의 경우 `/images` 폴더에 파일을 넣어주세요.

## About iOS Dev

### Swift & iOS

| 질문                                                                          |                          답변                          | 작성자 |
| :---------------------------------------------------------------------------- | :----------------------------------------------------: | :----: |
| ARC(Automatic Reference Counting)는 어느 시점에 작동하나요?                   |                 [ARC](/answers/arc.md)                 |  썽니  |
| strong, weak, unowned 키워드를 어떤 상황에서 사용하고, 차이는 무엇인가요?     |     [strong, weak, unowned](/answers/reference.md)     |        |
| 객체 간 순환참조를 발견하는 방법과 해결 방법은?                               | [Strong Reference Cycle](/answers/strong_ref_cycle.md) |  썽니  |
| Escaping Closure의 개념이 무엇인가요?                                         |                                                        |        |
| 타입 캐스팅을 할 때 사용하는 키워드인 as, as?, as! 이 셋의 차이는 무엇인가요? |                                                        |        |
| Swift에서 Class와 Struct의 차이는 무엇인가요?                                 |  [Class vs Struct](https://github.com/richoh86/iOS-Dev-Career/blob/develop/answers/ClassStruct.md)                                                      | [원석](https://github.com/richoh86/OhWonSeok_iOS_School6)       |
| 4.1 버전 미만과 최신버전에서의 배열의 메소드인 FlatMap의 차이는 무엇인가요?   |             [flatMap](/answers/flatmap.md)             |  썽니  |   
| GCD란?                                 |  [GCD](https://github.com/fomagran/iOS-Dev-Career/blob/fomagran/answers/GCD.md)                                                      | [Fomagran](https://github.com/fomagran)       |



### Layout

| 질문                                                                               |                    답변                    | 작성자 |
| :--------------------------------------------------------------------------------- | :----------------------------------------: | :----: |
| Frame 과 Bounds 의 차이는 무엇인가요?                                              | [Frame & Bounds](/answers/frame_bounds.md) |  썽니  |
| Top/BottomLayoutGuide가 iOS11에서 deprecate된 이유?                                |                                            |        |
| UIStackView의 장점은 무엇이라고 생각하시나요?                                      |                                            |        |
| Autolayout Constraint의 Priority의 개념이 무엇이고, 어떤상황에 사용하나요?         |                                            |        |
| Content Hugging Priority의 개념이 무엇이고, 어떤상황에 사용하나요?                 |                                            |        |
| UICollectionViewLayout클래스에 prepare 메소드는 어떤 역할을 하나요?                |                                            |        |
| UITableView를 구성할때 셀의 컨텐츠에 따라 높이를 설정하고싶다면 어떻게 해야하나요? |  [TableView](answers/tableview_height.md)  |  썽니  |
| StoryBoard가 Git 에서 충돌이 발생했습니다. 어떻게 해결하고 예방 하시겠습니까?      |                                            |        |

### Test

| 질문                                                                           |                    답변                    | 작성자 |
| :----------------------------------------------------------------------------- | :----------------------------------------: | :----: |
| 커스텀뷰 클래스 내 Private Method를 테스트 할 수 있는 방법은 무엇이 있나요?    | [Unit test](answers/test_privatemethod.md) |  썽니  |
| UITest를 UnitTest로 대체할 수 있는 방법은 무엇인가요?                          |                                            |        |
| Api서버를 강력하게 의존하는 뷰를 api요청없이 테스트 하는 방법은 무엇이 있나요? |                                            |        |

## About Computer Science

| 질문 | 답변 | 작성자 |
| :--- | :--: | :----: |
|      |      |        |

## About 마인드, 태도

| 질문 | 답변 | 작성자 |
| :--- | :--: | :----: |
|      |      |        |

## 기타 참고 자료

| 주제                    |                   답변                    | 작성자 |
| :---------------------- | :---------------------------------------: | :----: |
| iOS 안에는 뭐가 있을까? | [What's in iOS?](answers/whats_in_ios.md) |  썽니  |

## 질문 출처

- [룩핀 면접질문](https://medium.com/lookpin-engineering/ios-%EA%B0%9C%EB%B0%9C%EC%9E%90-%EB%A9%B4%EC%A0%91-%EC%A7%88%EB%AC%B8%EB%A6%AC%EC%8A%A4%ED%8A%B8-b92350a91c1b)  
- [JaeSungLee iOS Interviewquestions](https://github.com/JeaSungLEE/iOSInterviewquestions)
