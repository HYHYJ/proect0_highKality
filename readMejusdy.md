 <div align=start>

 # <strong>마켓컬리 Kurly</strong>
 
 
 
  <div align=center>
 
 ### 🍀<strong>Introduction</strong>
 안녕하세요. 마켓컬리를 진행한 팀<br />
 겁나 10조?입니다.  
<br/>   
  


 ### <strong>⭐Team members</strong>

 <img src="https://img.shields.io/badge/이재호-8572EE	?style=apple&logo=apple&logoColor=white"/>
  <img src="https://img.shields.io/badge/김남진-8572EE	?style=flat&logo=apple&logoColor=white"/>
    <img src="https://img.shields.io/badge/백상호-8572EE		?style=flat&logo=apple&logoColor=white"/>
      <img src="https://img.shields.io/badge/장효윤-8572EE		?style=flat&logo=apple&logoColor=white"/>   
  
<br/> 

 ### <strong>🔥SKILL</strong>

 <img src="https://img.shields.io/badge/HTML-F03F40?style=flat&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-0000FF?style=flat&logo=css3&logoColor=white"/>
    <img src="https://img.shields.io/badge/SASS-FF3CBB	?style=flat&logo=sass&logoColor=white"/>   
  
<br/>

<div align=start>  
  
### <strong>📃Completed Pages✏️</strong>  
    

+ <strong>Main</strong> - 장효윤
+ <strong>Register</strong> - 백상호
+ <strong>login</strong> - 김남진
+ <strong>Product-List</strong> - 이재호
+ <strong>Product-Detail</strong>- 장효윤
+ <strong>Cart</strong> - 김남진  
  <br/>

### <strong>🌊웹접근성 aria 사용법</strong>  
    

+ aria-lebal : button, 읽기어려운 글들을 aria-lebal로 값을 주었습니다.
+ aria-hidden="true" : 읽지 않아도되는 정보를 스크린리더가 읽지 않게 hidden 처리 헀습니다.
+ class="a11yHidden" : 화면에는 보이지않은 중요한 정보들을 보여주기 위해 사용했습니다.

### <strong>🎨성능 검사</strong>  
    

+ 스크린 리더 검사: 윈도우 내레이터 사용하여 웹접근성을 확인했습니다.


### <strong>🗝️프로젝트 한줄평</strong>  
    

+ 이재호:
+ 김남진:
+ 백상호:
+ 장효윤:



# <strong>✏️Main-page</strong>


진행자: 장효윤
### **🖥️Image**
 <img src="">


### **📌HTML 순서**(Main-page)
- &lt;main&gt;
  - &lt;section&gt; 메인 배너 섹션
  - &lt;section&gt; 오늘 추천상품 '이 상품 어때요?' 섹션
  - &lt;section&gt; 중간 서브 라인 배너 섹션
  - &lt;aside&gt; 최근 본 상품 오른쪽 사이드바
  - &lt;aside&gt; 뷰티컬리 광고 팝업창

<details>
<summary>📝HTML 상세코드보기</summary>
<div markdown="1">

```html 
    <main class="main__main">
      <!-- 메인 배너 섹션-->
      <section class="mainBanner">
        <h2 class="a11yHidden">메인 배너</h2>
        <figure class="mainBanner__imageBox">
          <img
            class="mainBanner__image"
            src="/images/banner05.png"
            alt="메인 광고배너 이미지"
          />
          <figcaption class="a11yHidden">
            컬리 장보기의 특권&#44; 이 주의 특가 한 눈에 보기&#44; 우측 상단
            특가 혜택에서 확인하세요
          </figcaption>
        </figure>
        <div class="mainBanner__page" aria-label="메인 배너 다섯 개중 첫번째">
          1&#47;5
        </div>
        <div class="mainBanner__buttonBox">
          <button
            class="mainBanner__button mainBanner__leftArrow"
            aria-label="메인배너 왼쪽으로 가기 버튼"
          ></button>
          <button
            class="mainBanner__button mainBanner__rightArrow"
            aria-label="메인배너 오른쪽으로 가기 버튼"
          ></button>
        </div>
        <!-- 오늘 추천상품 '이 상품 어때요?' 섹션 -->
      </section>
      <section class="recommendProduct">
        <h2 class="recommendProduct__title" aria-label="오늘 추천 상품">
          이 상품 어때요?
        </h2>
        <ul class="recommendProduct__list">
          <li class="recommendProduct__product" aria-label="상품 일번">
            <a href="/">
              <figure class="recommendProduct__image">
                <img
                  src="/images/product01.png"
                  alt="풀무원 탱탱쫄면 네개입 이미지"
                />
              </figure>
            </a>
            <a
              class="recommendProduct__name"
              href="/"
              aria-label="풀무원 탱탱쫄면 네개입"
              >&#91;풀무원&#93; 탱탱쫄면 &#40;4개입&#41;</a
            >
            <span
              class="recommendProduct__price"
              aria-label="가격 사만구천팔십 원"
              >4&#44;980 원</span
            >
            <button
              class="recommendProduct__cart"
              aria-label="장바구니 버튼"
            ></button>
          </li>
          <li class="recommendProduct__product" aria-label="상품 이번">
            <a href="/">
              <figure class="recommendProduct__image">
                <img
                  src="/images/product02.png"
                  alt="온더바디 죠르디 시카 자석 선쿠션 이미지"
                />
              </figure>
            </a>
            <a
              class="recommendProduct__name"
              href="/"
              aria-label="온더바디 죠르디 시카 자석 선쿠션"
              >&#91;온더바디&#93; 죠르디 시카 자석 선쿠션</a
            >
            <span
              class="recommendProduct__price"
              aria-label="가격 삼만이천오백 원"
              >32&#44;500 원</span
            >
            <button
              class="recommendProduct__cart"
              aria-label="장바구니 버튼"
            ></button>
          </li>
          <li class="recommendProduct__product" aria-label="상품 삼번">
            <a href="/">
              <figure class="recommendProduct__image">
                <img
                  src="/images/product03.png"
                  alt="유기농 밀키퀀 현미 이미지"
                />
              </figure>
            </a>
            <a
              class="recommendProduct__name"
              href="/"
              aria-label="유기농 밀키퀀 현미 사 키로그램"
              >유기농 밀키퀀 현미 4kg</a
            >
            <span class="recommendProduct__price" aria-label="가격 이만오천 원"
              >25&#44;000 원</span
            >
            <button
              class="recommendProduct__cart"
              aria-label="장바구니 버튼"
            ></button>
          </li>
          <li class="recommendProduct__product" aria-label="상품 사번">
            <a href="/">
              <figure class="recommendProduct__image">
                <img
                  src="/images/product04.png"
                  alt="프로쉬 베이비 세탁세 이미지"
                />
              </figure>
            </a>
            <a
              class="recommendProduct__name"
              href="/"
              aria-label="프로쉬 베이비 세탁세"
              >&#91;프로쉬&#93; 베이비 세탁세</a
            >
            <span class="recommendProduct__sale" aria-label="세일 이십사 퍼센트"
              >24&#37;</span
            >
            <span
              class="recommendProduct__price"
              aria-label="가격 만팔천구백 원"
              >18&#44;900 원</span
            >
            <span class="recommendProduct__beforePrice" aria-hidden="true"
              >24&#44;000 원</span
            >
            <button
              class="recommendProduct__cart"
              aria-label="장바구니 버튼"
            ></button>
          </li>
        </ul>
        <button
          class="recommendProduct__rightArrow"
          aria-label="추천상품 더보기 버튼"
        ></button>
      </section>
      <!-- 중간 서브 라인 배너 섹션-->
      <section class="lineBanner">
        <h2 class="a11yHidden">서브 라인 배너</h2>
        <figure class="lineBanner__imageBox">
          <img
            class="lineBanner__image"
            src="/images/line-banner1.png"
            alt="서브 라인 광고배너 이미지"
          />
          <figcaption class="a11yHidden">
            더 풍성해진 10월 퍼플위크 이벤트 진행&#44; 적립률 올라가고 3종
            쿠폰팩 증정
          </figcaption>
        </figure>
      </section>
      <!-- 오늘 추천상품 '놓치면 후회할 가격' 섹션 -->
      <section class="recommendProduct">
        <h2 class="recommendProduct__title" aria-label="좋은 가격 상품">
          놓치면 후회할 가격
        </h2>
        <ul class="recommendProduct__list">
          <li class="recommendProduct__product" aria-label="상품 일번">
            <a href="/">
              <figure class="recommendProduct__image">
                <img
                  src="/images/product01.png"
                  alt="풀무원 탱탱쫄면 네개입 이미지"
                />
              </figure>
            </a>
            <a
              class="recommendProduct__name"
              href="/"
              aria-label="풀무원 탱탱쫄면 네개입"
              >&#91;풀무원&#93; 탱탱쫄면 &#40;4개입&#41;</a
            >
            <span
              class="recommendProduct__price"
              aria-label="가격 사천구백팔십 원"
              >4&#44;980 원</span
            >
            <button
              class="recommendProduct__cart"
              aria-label="장바구니 버튼"
            ></button>
          </li>
          <li class="recommendProduct__product" aria-label="상품 이번">
            <a href="/">
              <figure class="recommendProduct__image">
                <img
                  src="/images/product02.png"
                  alt="온더바디 죠르디 시카 자석 선쿠션 이미지"
                />
              </figure>
            </a>
            <a
              class="recommendProduct__name"
              href="/"
              aria-label="온더바디 죠르디 시카 자석 선쿠션"
              >&#91;온더바디&#93; 죠르디 시카 자석 선쿠션</a
            >
            <span
              class="recommendProduct__price"
              aria-label="가격 삼이천오백 원"
              >32&#44;500 원</span
            >
            <button
              class="recommendProduct__cart"
              aria-label="장바구니 버튼"
            ></button>
          </li>
          <li class="recommendProduct__product" aria-label="상품 삼번">
            <a href="/">
              <figure class="recommendProduct__image">
                <img
                  src="/images/product03.png"
                  alt="유기농 밀키퀀 현미 이미지"
                />
              </figure>
            </a>
            <a
              class="recommendProduct__name"
              href="/"
              aria-label="유기농 밀키퀀 현미 4키로그램"
              >유기농 밀키퀀 현미 4kg</a
            >
            <span class="recommendProduct__price" aria-label="가격 이만오천 원"
              >25&#44;000 원</span
            >
            <button
              class="recommendProduct__cart"
              aria-label="장바구니 버튼"
            ></button>
          </li>
          <li class="recommendProduct__product" aria-label="상품 사번">
            <figure class="recommendProduct__image">
              <img
                src="/images/product04.png"
                alt="프로쉬 베이비 세탁세 이미지"
              />
            </figure>
            <a
              class="recommendProduct__name"
              href="/"
              aria-label="프로쉬 베이비 세탁세"
              >&#91;프로쉬&#93; 베이비 세탁세</a
            >
            <span class="recommendProduct__sale" aria-label="세일 이십사 퍼센트"
              >24&#37;</span
            >
            <span
              class="recommendProduct__price"
              aria-label="가격 만팔천구백 원"
              >18&#44;900 원</span
            >
            <span class="recommendProduct__beforePrice" aria-hidden="true"
              >24&#44;000 원</span
            >
            <button
              class="recommendProduct__cart"
              aria-label="장바구니 버튼"
            ></button>
          </li>
        </ul>
        <button
          class="recommendProduct__rightArrow"
          aria-label="추천상품 더보기 버튼"
        ></button>
      </section>
      <!-- 최근 본 상품 오른쪽 사이드바 -->
      <aside>
        <section class="recentProduct">
          <h2>최근 본 상품</h2>
          <ul class="recentProduct__list">
            <li class="recentProduct__item">
              <a href="/">
                <img
                  src="/images/product01.png"
                  alt="풀무원 탱탱쫄면 네개입 이미지"
                />
              </a>
            </li>
            <li class="recentProduct__item">
              <a href="/">
                <img
                  src="/images/product04.png"
                  alt="프로쉬 베이비 세탁세 이미지"
                />
              </a>
            </li>
            <li class="recentProduct__item">
              <a href="/">
                <img
                  src="/images/product02.png"
                  alt="온더바디 죠르디 시카 자석 선쿠션 이미지"
                />
              </a>
            </li>
          </ul>
          <button
            class="recentProduct__buttonUp recentProduct__sprite"
            aria-label="최근 본 상품 위로가기 버튼"
          ></button>
          <button
            class="recentProduct__buttonDown recentProduct__sprite"
            aria-label="최근 본 상품 아래로가기 버튼"
          ></button>
        </section>
      </aside>
      <!-- 뷰티 플랫폼 광고 팝업창 -->
      <aside class="mainPopup">
        <figure>
          <img src="/images/mainPopup.png" alt="뷰티컬리 광고팝업창" />
          <figcaption class="a11yHidden">
            처음 만나는 뷰티 플랫폼 뷰티컬리 지금바로 만나보세요
          </figcaption>
        </figure>
        <button class="mainPopup__closeTodayButton">오늘 하루 안보기</button>
        <button class="mainPopup__closeButton">닫기</button>
      </aside>
    </main>
```
</div>
</details>

----

 <div align=start>

### **📌SASS 진행코드**(Main-page)
<details>
<summary>📝SASS 상세코드보기</summary>
<div markdown="1">

```scss
@use "../utils" as *;
@use "../components" as *;


/* Accessibility Styles */
.a11yHidden {
  @include a11yHidden;
}
/* 전체 magin없애기, width 100% */
.main__main {
  margin: 0;
  width: 100%;
  font-family: Pretendard;
  position: relative;
  
  // 메인 배너 
  & .mainBanner {
    position: relative;
    padding: 0;
  }
}
.mainBanner{
  //메인 배너 이미지
  &__image {
    width: 100%;
  }
  // 메인 배너 페이지 수 표시 박스
  &__page {
    @include posRightTop($r: 22%, $t: 87%);
    background: rgba(0, 0, 0, 15%);
    width: rem(47px);
    height: rem(18px);
    font-size: rem(13px);
    font-weight: 600;
    color:$white;
    border-radius: rem(12px);
    padding: auto;
    text-align: center;
  }
  // 메인 배너 옆으로 가기 버튼
  &__button {
    cursor: pointer;
    @include pos;
    top: 38%;
    width: rem(52px);
    height: rem(52px);
    border-radius: 50%;
    border: 0;
    background: rgba(0, 0, 0, 10%) url("/images/Icon/Arrow.png");
  }
  &__rightArrow {
    transform: scaleX(-1);
    right: 17%;
  }
  &__leftArrow {
    left: 17%;
  }

}

// 오늘 추천 상품 섹션 
.recommendProduct {
  position: relative;
  width: rem(1050px);
  // height: 650px; 
  @include autoMargin;
  padding: rem(70px) 0;
  box-sizing: border-box;
  // 이 상품 어때요?, 놓치면 후회할 가격 부분 
  &__title {
    font-size: rem(27px);
    font-weight: 700;
    padding: rem(15px) 0;
    text-align: center;
    margin-bottom: rem(30px);
  }
  // 상품 리스트 부분 
  &__list {
    list-style: none;
    padding-left: 0;
    @include flexbox($justify: space-between);
  }
  //상품 각 박스 부분
  &__product {
    position: relative;
    width: rem(249px);
    height: rem(426px);
  }
  // 상품 이름 
  &__name {
    text-decoration: none;
    color:$black;
    font-size: rem(14px);
    padding: rem(18px) 0;
    display: block;
  }
  // 상품 가격 
  &__price {
    font-size: rem(22px);
    font-weight: bold;
  }
  // 상품 세일 글자 
  &__sale {
    color: orangered;
    font-size: rem(22px);
    font-weight: 800;
  }
  // 네번째 상품에 중간선 있는 이전 가격 
  &__beforePrice {
    display: block;
    text-decoration: line-through;
    color:$gray-300;
    font-size: rem(13px);
    margin-top: rem(16px);
  }
  // 상품사진 하단오른쪽에 있는 장바구니 버튼 
  &__cart {
    cursor: pointer;
    @include pos;
    bottom: 30%;
    right: 8%;
    background: #2a0038 url("/images/Icon/Cart.png");
    background-position: center;
    opacity: 50%;
    width: rem(42px);
    height: rem(42px);
    border-radius: 50%;
    border: 0;
  }
  
  // 추천 상품 더보기 버튼 
  &__rightArrow {
    cursor: pointer;
    background:$white url("/images/Icon/rightArrow_black.png") no-repeat;
    width: rem(50px);
    height: rem(50px);
    border-radius: 50%;
    border: none;
    background-position: center;
    box-shadow: 0 0 rem(10px) $gray-100;
    position: absolute;
    top: 45%;
    right: -2.4%;
  }
}

// 서브 라인배너 
.lineBanner {
  width: rem(1050px);
  margin: rem(40px) auto;
  padding: 0;
}

// 최근 본 상품 
.recentProduct {
  position: relative;
  position: fixed;
  top: 50%;
  right: 2%;
  width: rem(74px);
  height: rem(223px);
  font-size: rem(7px);
  text-align: center;
  padding: rem(35px) 0;
  border: 1px solid $gray-200;
  box-sizing: border-box;
  background: $white;
  // 최근 본 상품 이미지 공통 넓이 
  & img {
    width: 100%;
  }
  // 최근 본 상품 이미지 리스트 박스 
  &__list {
    list-style: none;
    padding: 0;
    width: rem(40px);
    height: rem(129px);
    overflow: hidden;
    row-gap: rem(2px);
    @include autoMargin;
    margin-top: rem(10px);
  }
  // 최근 본 상품 버튼
  &__sprite {
    cursor: pointer;
    width: rem(18px);
    height: rem(18px);
    background: url("/images/Icon/Arrow-2.png");
    position: absolute;
    border: none;
  }
  // 최근 본 상품 위로가기 버튼
  &__buttonUp {
    background-position: 50% 10%;
  
    top: 4%;
    right: 37%;
  }
  // 최근 본 상품 위로가기 버튼
  &__buttonDown {
    background-position: 50% 35%;
    bottom: 4%;
    right: 37%;
  }
}


// 메인 뷰티컬리 광고 팝업창 
.mainPopup {
  width: rem(345px);
  height: rem(530px);
  border-radius: rem(16px);
  background: $white;
  box-shadow: 0 rem(8px) rem(36px) 0 $gray-200;
  color: $content;
  font-weight: 700;
  position: fixed;
  bottom: rem(10px);
  left: rem(7px);
  
  & img {
    border-radius: rem(16px) rem(16px) 0 0;
  }
  & &__closeButton{
    border-left: solid rem(1px) $gray-100;
  }
  // 뷰티컬리 팝업 누르면 사라짐
  &:active {
    visibility: hidden;
  }
}

// 뷰티컬리 팝업 닫기 버튼 
button[class*="mainPopup__close"] {
  cursor: pointer;
  height: rem(60px);
  background: transparent;
  width: 49%;
  display: inline-block;
  margin: 0;
  border: 0;
}
```
</div>
</details>  

<br/>


# <strong>🛍️Product Detail-page</strong>


진행자: 장효윤
### **🖥️Image**
 <img src="">


### **📌HTML 순서**(Product Detail-page)
- &lt;main&gt;
  - &lt;section&gt; 상품 상세설명 섹션
    - &lt;div&gt; 상품 제목박스
    - &lt;figure&gt; 상품 이미지
    - &lt;dl&gt; 상품 설명 리스트
    - &lt;div&gt; 상품 결제박스
  
  <br />
  
  - &lt;section&gt; 상품 상세페이지 섹션
    - &lt;div&gt; 상품 전체 상세페이지 박스
    - &lt;div&gt; 설명,정보,후기,문의 페이지 이동 박스

<details>
<summary>📝HTML 상세코드</summary>
<div markdown="1">

```html 
    <main>
      <section class="productDetail">
        <div class="productDetail__titleBox">
          <h2 class="productDetail__title" aria-label="풀무원 탱탱쫄면 네개입">
            &#91;풀무원&#93; 탱탱쫄면 &#40;4개입&#41;
          </h2>
          <span class="productDetail__starDelivery">샛별배송</span>
          <span class="productDetail__sub">튀기지 않아 부담없는 매콤함</span>
          <span
            aria-label="가격 사천구백팔십원"
            class="productDetail__fontSizeXl"
            >4&#44;980 <span class="productDetail__fontSizeS">원</span></span
          >
          <span class="productDetail__PurpleSpan"
            >로그인 후&#44; 적립 혜택이 제공됩니다&#46;</span
          >
        </div>
        <figure class="productDetail__image">
          <img
            src="/images/product01.png"
            alt="풀무원 탱탱쫄면 네개입 이미지"
          />
        </figure>
        <dl class="productDetail__list">
          <div class="productDetail__item">
            <dt>배송</dt>
            <dd>
              <span class="productDetail__fontBold">샛별배송</span><br />
              23시 전 주문시 내일 아침 7시 전 도착<br />
              &#40;대구 부산 울산 샛별배송 운영시&#59;간 별도 확인&#41;
            </dd>
          </div>
          <div class="productDetail__item">
            <dt>판매자</dt>
            <dd class="productDetail__fontBold">칼리</dd>
          </div>
          <div class="productDetail__item">
            <dt>포장타입</dt>
            <dd>
              <span class="productDetail__fontBold" aria-label="상온 종이 포함"
                >상온 (종이 포함)</span
              >
              <br />택배배송은 에코 포장이 스티로폼으로 대체됩니다&#46;
            </dd>
          </div>
          <div class="productDetail__item">
            <dt>판매단위</dt>
            <dd class="productDetail__fontBold" aria-label="백이십삼그램 한봉">
              1봉
            </dd>
          </div>
          <div class="productDetail__item">
            <dt>중량&#47;용량</dt>
            <dd class="productDetail__fontBold" aria-label="백이십삼그램 네봉">
              123g&#42;4봉
            </dd>
          </div>
          <div class="productDetail__item">
            <dt>원산지</dt>
            <dd class="productDetail__fontBold">상세페이지 별도표기</dd>
          </div>
          <div class="productDetail__item">
            <dt>알레르기정보</dt>
            <dd class="productDetail__allegyDd">
              &#8208;대두&#44; 밀&#44; 쇠고기 함유<br />
              &#8208;계란&#44; 우유&#44; 메밀&#44; 땅콩&#44; 고등어&#44; 게&#44;
              돼지고기&#44; 새우&#44; 복숭아&#44; 토마토&#44; 아황산류&#44;
              호두&#44; 잣&#44; 닭<br />고기&#44;오징어&#44; 조개류(굴&#44;
              전복&#44; 홍합 포함)를 사용한 제품과 같은 제조시설에서 제조
            </dd>
          </div>
          <div class="productDetail__item">
            <dt>상품선택</dt>
            <dd>
              <div class="productDetail__select">
                <span>&#91;풀무원&#93; 탱탱쫄면 &#40;4개입&#41;</span>
                <div class="productDetail__selectBox">
                  <button type="button" class="productDetail__minus"></button>
                  <span class="productDetail__selectBoxOne">1</span>
                  <button type="button" class="productDetail__plus"></button>
                </div>
                <span
                  class="productDetail__selectPrice"
                  aria-label="사천구백팔십원"
                  >4&#44;980원</span
                >
              </div>
            </dd>
          </div>
        </dl>
        <div class="productDetail__productcart">
          <dl class="productDetail__allPrice">
            <dt>총 상품금액&#58;</dt>
            <dd aria-label="사천구백팔십원">
              <span class="productDetail__fontSizeXl">4&#44;980</span> 원
            </dd>
          </dl>
          <div class="productDetail__point">
            <span class="productDetail__pointIcon">적립</span>
            <span>로그인 후&#44; 적립 혜택 제공</span>
          </div>
          <div class="productDetail__allButton">
            <button
              class="productDetail__heart productDetail__button"
              aria-label="상품 좋아요 버튼"
            ></button>
            <button
              class="productDetail__alarm productDetail__button"
              aria-label="상품 알림 버튼"
            ></button>
            <button
              class="productDetail__cartButton"
              aria-label="장바구니 담기 버튼"
            >
              장바구니 담기
            </button>
          </div>
        </div>
      </section>
      <!-- description -->
      <section class="description">
        <div class="description__content">
          <h3 class="a11yHidden">상품설명</h3>
          <figure class="description__image">
            <img src="/images/product01-2.png" alt="풀무원 탱탱 쫄면 네개입" />
          </figure>
          <div class="description__titleBox">
            <span class="description__subTitle"
              >튀기지 않아 부담없는 매콤함</span
            >
            <span class="description__title">&#91;풀무원&#93; 탱탱쫄면</span>
          </div>
          <p class="description__p">
            쫄면의 진가는 매콤새콤한 양념과 탱탱한 면발에서 찾을 수 있지요&#46;
            풀무원은 이 맛을 더 부담 없이 즐길 수 있도록 튀기지 않고 만든
            탱탱쫄면을 선보입니다&#46; 밀가루와 감자 전분을 적절히 배합해 탄력이
            좋고&#44; 입에 넣었을 때는 찰지게 씹히죠&#46; 고추장을 넣어 숙성한
            비빔장은 자연스럽고 깊은 맛을 냅니다&#46; 간단하게 조리해 마지막 한
            가닥까지 탱탱한 식감을 즐겨보세요&#46; 취향에 따라 다양한 고명을
            올려 드셔도 좋아요&#46;
          </p>
          <span class="description__checkPointTitle"
            >Karly&#96;s Check Point</span
          >
          <figure class="description__descriptionImage">
            <img
              src="/images/description-1.png"
              alt="생산 유통 과정 활용법 브랜드와 생산자 설명 이미지"
            />
            <figcaption class="a11yHidden">
              생산 유통 과정은 튀기지 않고 바람으로 말린면이다&#46; 활용법은
              온가족이 즐기기 좋은 4개입 포장과 간편한 조리로 완성하는
              쫄면이다&#46; 브랜드와 생산자는 풀무원이다&#46;
            </figcaption>
          </figure>
          <h3 class="a11yHidden">상세정보</h3>
          <figure class="description__descriptionImage2">
            <img src="/images/description-2.png" alt="쫄면의 영양정보 이미지" />
            <figcaption class="a11yHidden">
              풀무원 탱탱 쫄면은 123그램 4개입이다&#46; 쫄면의 영양정보 이미지
            </figcaption>
          </figure>
          <div class="whyKarly">
            <span class="whyKarly__title">WHY KARLY</span>
            <div class="whyKarly__sub">
              <div class="whyKarly__item">
                <div class="whyKarly__roundIcon whyKarly__check"></div>
                <span class="whyKarly__subTitle">깐깐한 상품위원회</span>
                <p class="whyKarly__p">
                  나와 내 가족이 먹고 쓸 상품을 고르는 마음으로 매주 상품을 직접
                  먹어보고&#44; 경험해보고 성분&#44; 맛 안정성 등 다각도의
                  기준을 통과한 상품만을 판매합니다&#46;
                </p>
              </div>
              <div class="whyKarly__item">
                <div class="whyKarly__roundIcon whyKarly__web"></div>
                <span class="whyKarly__subTitle">차별화된 Karly Only 상품</span>
                <p class="whyKarly__p">
                  전국 각지와 해외의 훌륭한 생산자가 믿고 선택하는 파트너&#44;
                  마켓칼리&#46; 3천여 개가 넘는 칼리 단독 브랜드&#44; 스펙의
                  Karly Only 상품을 믿고 만나보세요&#46;
                </p>
              </div>
              <div class="whyKarly__item">
                <div class="whyKarly__roundIcon whyKarly__delivery"></div>
                <span class="whyKarly__subTitle">신선한 풀콜드체인 배송</span>
                <p class="whyKarly__p">
                  온라인 업계 최초로 산지에서 문 앞까지 상온&#44; 냉장&#44; 냉동
                  상품을 분리 포장 후 최적의 온도를 유지하는 냉장 배송
                  시스템&#44; 풀콜드체인으로 상품을 신선하게 전해드립니다&#46;
                </p>
              </div>
              <div class="whyKarly__item">
                <div class="whyKarly__roundIcon whyKarly__price"></div>
                <span class="whyKarly__subTitle"
                  >고객&#44; 생산자를 위한 최선의 가격</span
                >
                <p class="whyKarly__p">
                  매주 대형 마트와 주요 온라인 마트의 가격 변동 상황을 확인해
                  신선식품은 품질을 타협하지 않는 선에서 최선의 가격으로&#44;
                  가공식품은 언제나 합리적인 가격으로 정기 조정합니다&#46;
                </p>
              </div>
              <div class="whyKarly__item">
                <div class="whyKarly__roundIcon whyKarly__recycle"></div>
                <span class="whyKarly__subTitle"
                  >환경을 생각하는 지속 가능한 유통</span
                >
                <p class="whyKarly__p">
                  친환경 포장재부터 생산자가 상품에만 집중할 수 있는 직매입
                  유통구조까지&#44; 지속 가능한 유통을 고민하며 컬리를 있게 하는
                  모든 환경&#40;생산자&#44;커뮤니티&#44;직원&#41;이 더 나아질 수
                  있도록 노력합니다&#46;
                </p>
              </div>
            </div>
          </div>
          <div class="productReview">
            <h3 class="productReview__title">상품후기</h3>
            <span class="productReview__sub"
              >글후기 50원 적립금 혜택이 있어요&#46;</span
            >
            <ul class="productReview__descriptList">
              <li>
                퍼플&#44; 더퍼플은 2배 적립 &#40;100원&#41; &#47; 주간 베스트
                후기로 선정 시 5&#44;000원 추가 적립
              </li>
              <li>후기 작성은 배송완료일로부터 30일 이내 가능합니다&#46;</li>
              <li>
                작성하신 후기는 확인 후 적립금이 지급됩니다&#46; &#40;영업일
                기준 평균 1~2일 소요&#41;
              </li>
            </ul>
            <button
              class="productReview__button"
              aria-label="후기 작성하기 버튼"
            >
              후기 작성하기
            </button>
          </div>
        </div>
        <div class="description__buttonBox">
          <button
            class="description__button description__buttonPurple"
            type="button"
            aria-label="상품설명 이동 버튼"
          >
            상품설명
          </button>
          <button
            class="description__button"
            type="button"
            aria-label="상세정보 이동 버튼"
          >
            상세정보
          </button>
          <button
            class="description__button"
            type="button"
            aria-label="상품후기 이동 버튼 후기 천개"
          >
            후기<span class="productDetail__sub">&#40;1,000&#41;</span>
          </button>
          <button
            class="description__button"
            type="button"
            aria-label="문의 이동 버튼"
          >
            문의
          </button>
        </div>
      </section>
    </main>
```
</div>
</details>

----
### **📌SASS 진행코드**(Product Detail-page)
<details>
<summary>📝SASS 상세코드</summary>

```scss
@use "../utils" as *;
@use "../components" as *;
//제품 설명 박스
.productDetail{
  position: relative;
  width: rem(1050px);
  font-family: Pretendard;
  font-size: rem(16px); 
  @include autoMargin;
  padding: rem(60px) 0;
  box-sizing: border-box;

  //제품 설명 제목 묶음
  &__titleBox{
    @include flexbox($direction: column);
    row-gap: rem(16px);
  }
  //제목 맨위 샛별배송 글자 위치/스타일링
  &__starDelivery{
    order: -1;
    color: $gray-500;
    font-size: rem(21px);
    font-weight: 800;
  }
  //설명 제목
  &__title {
    font-size: rem(27px);
    font-weight: 700;
  }
  //설명 서브제목
  &__sub{
    color: $gray-400;
    line-height: 160%;
  }
  //설명 박스를 margin left줘서 이미지가 위치할 수있도록 한다.
  &__productcart, &__list, &__titleBox, &__productcart {
    margin-left: 480px;
  }
  //제품 이미지
  &__image{
    @include pos;
    top: 60px;
  }
  &__fontSizeXl{
    color: $gray-800;
    font-size: rem(29px);
    font-weight: 600;
    line-height: 150%;
  }
  &__fontSizeS {
    color: $gray-800;
    font-weight: 700;
    line-height: 140%;  
  }
  &__PurpleSpan {
    color: $primary;
    font-family: Pretendard;
    font-weight: 600;
    line-height: 150%;
    margin-bottom: 20px;
  }
  //상품상세 설명표 리스트
  &__item{
    display: flex;
    @include paddingY(16px);
    border-top: 1px solid $gray-100; 
    font-size: rem(12px);
  }
  &__item:last-child{
    border-bottom: 1px solid $gray-100;
  }
  //상품상세 설명표 리스트 dt
  &__item dt {
    width: rem(128px);

  }
  &__item &__fontBold {
    color: $gray-700;
    width: rem(128px);
    line-height: 150%;
    margin-bottom: rem(10px);
  }
 //상품상세 설명표 리스트 dd
  &__item dd {
    display: span;
    color: $gray-500;
  }

  &__allegyDd {
    display: block;
    width: rem(432px);
  }
  //상품 선택 할 수 있는 박스
  &__select {
    position: relative;
    width: rem(432px);
    height: rem(83px);
    border: rem(1px) solid $gray-100;
    color: $gray-600;
    font-weight: 600;
    @include padding(12px);
  }
  //상품 총 가격
  &__selectPrice{
    @include pos;
    font-size: rem(15px);
    font-weight: 700;
    bottom: rem(12px);
    right: rem(12px);
  }
  //상품 수량 선택 박스
  &__selectBox {
    height: rem(30px);
    width: rem(83px);
    border: rem(1px) solid $gray-200;
    margin-top: rem(12px);
    text-align: center;
  }
  
  &__plus{
    cursor: pointer;
    background: url('/images/Icon/Plus.png');
    width: 28px;
    height: 30px;
    border: none;
    background-position: 50% 17%;
    float: right;
  }
  &__minus{
    cursor: pointer;
    background: url('/images/Icon/Minus.png');
    width: 28px;
    height: 30px;
    border: none;
    background-position: 50% 87%;
    float: left;
    
  }
  &__selectBoxOne {
    display: inline-block;
    padding: auto 0;
    transform: translateY(8px);
    font-weight: 800;

  }
 //총 상품금액
  &__allPrice {
    @include flexbox($justify: flex-end, $items: center);
    column-gap: rem(17px);
    font-size: 16px;
    font-weight: 600;
    line-height: 150%;
    margin-top: rem(28px);

  }
  //포인트 적립 안내글
  &__point{
    margin-top: rem(9px);
    text-align: end;
    font-size: 16px;
    font-weight: 600;
    margin-bottom: rem(28px);
  }
  &__pointIcon{
    border-radius: 12px;
    background: $orange;
    width: rem(34px);
    height: rem(24px);
    text-align: center;
    color: $white;
    font-size: 10px;
    line-height: 160%;
    padding: 4px 8px;
    margin-right: 3px;

  }
  // 알림, 좋아요, 장바구니 버튼
  &__allButton {
    @include flexbox($justify: space-between)
  }
  &__button {
    cursor: pointer;
    width: 56px;
    height: 56px;
    padding: 4px;
    border: 1px solid $gray-100;
    // background: $white;
  }
  &__heart{
    background: url('/images/Icon/Squre.png');
    background-position: 50% 89% ;
  }
  &__alarm{
    background: url('/images/Icon/bell-2.png') no-repeat;
    background-position: 55% 50%;
  }
  &__cartButton {
    cursor: pointer;
    border-radius: 4px;
    background: $primary;
    width: rem(430px);
    height: rem(54px);
    color: $white;
    font-weight: 600;
    margin-bottom: rem(48px);
  }
}

//상세페이지 섹션
.productDetail__list .productDetail__item{
  display: flex;
}

// 이미지 상세페이지 부분
.description{
  position: relative;
  width: rem(1050px);
  font-family: Pretendard;
  font-size: rem(16px);
  @include flexbox($direction: column-reverse);
  @include autoMargin;
  //상세페이지 첫번째 이미지
  &__image img{
    width: 100%;
    margin-top: rem(40px);
  }
  //상세페이지 제목 박스
  &__titleBox {
    color: $black;
    @include flexbox($direction: column);
    @include padding(76px);
    text-align: center;
    border-bottom: 1px solid $gray-100;
  }
  //상세페이지 서브 제목
  &__subTitle {
    
    font-size: rem(28.43px);
    font-weight: 600;
    line-height: 150%;
  }
  //상세페이지 제목
  &__title {
    font-size: rem(50.517px);
    font-weight: 700;
    line-height: 140%;
  }
  //상세페이지 제품 설명글
  &__p {
    margin-top: rem(40px);
    padding-bottom: rem(200px);
    border-bottom: 1px solid $gray-100;
  }
  //상세페이지 컬리가 제품설명하는 글
  //제목
  &__checkPointTitle{
    display: block;
    @include autoMargin;
    width: rem(520px);
    font-size: rem(50.517px);
    font-weight: 700;
    line-height: 140%;
    background-color: $white;
    transform: translateY(-40px);
    margin-bottom: rem(70px);
  }
  //상세페이지 컬리가 제품설명하는 이미지
  &__descriptionImage{
    margin-bottom: rem(96px);

  }
  //제품설명, 상세정보, 후기, 문의 버튼바 
  &__button{
    cursor: pointer;
    height: rem(54px);
    width: 25%;
    float: left;
    border-radius: 0;
    border: 1px solid $gray-200;
    background: #F9F9F9;
    font-size: 16px;
    font-weight: 600;
    line-height: 150%;

  }
  &__button span{
    padding-left: rem(5px);
    font-size: rem(12.003px);
    line-height: 160%;
  }
  &__buttonPurple{
    background: $white;
    color: $primary;
    border: 1px solid#e0e0e0;
  }
}
//Why karly 부분
.whyKarly{
  @include marginY(84px);
  @include paddingX(12px);

  &__title{
    display: block;
    text-align: center;
    font-size: 28.43px;
    font-weight: 700;
    line-height: 140%;
    margin-bottom: rem(35px);
  }
  &__sub{
    @include flexbox($justify: center,
    $wrap: wrap);
    margin-bottom: rem(136px);
  }
  &__item{
    text-align: center;
    box-sizing: border-box;
    width: rem(315px);
    padding-top: rem(56px);
  }
  &__roundIcon{
    width: 40px;
    height: 40px;
    @include autoMargin;
    margin-bottom: rem(16px);
  }
  &__check {
    background: url('/images/Icon/check-list-purple.svg');
  }
  &__web {
    background: url('/images/Icon/web-purple.svg');
  } &__delivery {
    background: url('/images/Icon/delivery-purple.svg');
  } &__price {
    background: url('/images/Icon/price-plus-purple.svg');
  } &__recycle {
    background: url('/images/Icon/recycle-purple.svg');
  }

  &__subTitle{
    color: $primary;
    font-size: rem(21.328px);
    font-weight: 600;
    line-height: 150%;
    
  }
  &__sub p{
    padding-top: rem(24px);
    @include autoMargin;
    line-height: 160%;
    width: 77%;
  }
}
//상품 후기 부분
.productReview{
  position: relative;
  padding-bottom: rem(136px);

  &__title{
    font-size: rem(28.43px);
    font-weight: 700;
    line-height: 140%;
    margin-bottom: rem(30px);
  }
  &__sub{
    color: $gray-800;
    font-weight: 600;
    line-height: 150%;
  }
  //
  &__descriptList{
    
    color: $gray-500;
    font-size: rem(12px);
    font-weight: 600;
    line-height: 150%;
    margin-left: 1.5%;
    list-style-type: disc;
  }
  
  // 후기 작성하기 버튼
  &__button{
    cursor: pointer;
    @include posRightTop($r:0, $t:0);
    color: $white;
    border-radius: 4px;
    background: $primary;
    width: 155px;
    height: 44px;
    border: 0;
  }
}


```
</div>
</details>  

<br />
