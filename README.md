# Java Calculator Precourse

## 구현할 기능 목록

### 1. 계산기 클래스
- **목적**: 계산 기능 제공

### 2. 구분자 클래스
- **기능**:
  1. 파라미터(구분자) 관리
  2. 숫자 관리

### 3. 에러 핸들러
- **기능**:
  1. 잘못된 파라미터 처리
  2. 파라미터 개수 초과 처리
  3. 파라미터가 숫자로 시작하는지 검증
  4. 파라미터로 끝날 때 처리

### 4. 계산 서비스
- **기능**:
  1. 파라미터 체크
  2. 새로운 파라미터 삽입 기능
  3. 숫자들 추출
  4. 메인 계산 로직

## MVC 패턴
- **구성**:
  - **Service**: 비즈니스 로직 처리
  - **View**: 사용자 인터페이스 관리
  - **Controller**: 사용자 입력과 서비스 간의 중재 역할

이 구조를 통해 코드의 가독성을 높이고, 유지보수가 용이한 설계를 목표로 합니다.
