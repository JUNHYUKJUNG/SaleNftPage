# PFP Project

Mint NFT Contract Address - 0x70F216E5070baf9768e2Ab6327718DfFC2486B0C

Sale NFT Contract Address -
0x1355d781c16D9aDe4Ec4b1eEEd1f5EEad3B5B47A

리믹스로 스마트컨트랙트 만들고
CRA - frontend 생성
모두다 git으로 하기 위해
gitignore
: .env .deps artifacts 추가
readme.md
: contract 주소

Tailwind 설치 react router dom 설치
레이아웃 작업
: 메타마스크 세팅, 웹3 세팅

Header는 타입 지정하고 props로 받아주면 됨
outlet은 레이아웃에 있는 값들에 접근하기 위해서는 리액트라우터돔에서 제공하는 outlet context기능활용(전역상태변수)

사용하는 위치에서 useOutletContext로 꺼내오기만 하면 됨. 제네릭으로 <OutletContext> 꺼내오면 됨.

그 후 기능들을 하나하나씩 붙여나가면 됨
Ex) mint modal 기능
