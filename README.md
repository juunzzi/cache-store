# cache-store
나의 작고 귀여운 캐시스토어 🥰 (난 같은 코드를 계속 반복하고 있었다....)

## 동기

[ ] Remote Data를 요청하는 코드를 짜고 있다면 ? 수 초내의 발생하는 재 요청에 어떻게 응답할 것 인가..

[ ] React 영역으로 확장 ? 

[ ] Lovely Apollo, React-Query, Use-SWR

## 아이디어

[ ] 캐시 데이터가 구식이 되는 것을 방지하기 위해 10초 후에 파기한다. (디바운싱을 활용하여 마지막 요청으로 부터 10초를 유지한다)

[ ] 캐시 스토어 객체에 직접 접근하는 함수 + `cache` 데이터 + `timeout` 데이터 캡슐화

[ ] cachingAPI : cache key와 remote API fetcher 함수를 인자로 받는다. 흔하디 흔한 고차함수 중 하나이다. `setCache,getCache` 함수 직접 호출가능.
