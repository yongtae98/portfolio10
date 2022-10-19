<template>
  <v-app id="home">
    <NavBar />
    <v-container fluid>
      <div class="head">
        <v-row>
          <v-col cols="5">
            <div style="position: relative" class="mt-16">
              <h1 class="text-yellow">최용태</h1>
              <h1 class="text-yellow">포트폴리오 디자인</h1>
              <span class="text-yellow">Web Designer & Developer</span><br />

              <v-btn tile dark class="text-yellow mt-8" variant="outlined">
                START
              </v-btn>
            </div>
          </v-col>
          <v-col cols="2">
            <div
              style="
                position: absolute;
                z-index: 9999;
                bottom: 0;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
              class="mt-16"
            >
              <v-icon>fas fa-angle-double-down</v-icon>
            </div>
          </v-col>
          <v-col cols="5">
            <div style="position: relative; z-index: 9999" class="mt-16">
              <v-img src="p3.png" contain max-height="300"></v-img>
            </div>
          </v-col>
        </v-row>
      </div>
      <v-col cols="12" class="mt-16" id="about">
        <div>
          <v-row>
            <v-col cols="12" sm="6">
              <div class="egh">
                <v-img src="b1.jpg" max-height="400" class=""></v-img>
              </div>
            </v-col>
            <v-col cols="12" sm="6">
              <h2 class="mt-16 text-red">About Me</h2>
              <br />
              <div style="width: 120px"></div>
              <h4 class="mt-n4"></h4>
              <h4>이름: 최용태</h4>
              <h4>학교전공: 명지전문대학교 정보통신공학과</h4>
              <h4>연락처: 010-4065-9134</h4>
              <h4>메일주소:choiyt3939@naver.com</h4>
              <br />
              <h4>나의 소개</h4>
              <p class="text-grey">
                저는 두원공과대학교에서 정보통신공학과를 졸업했고 주로
                네트워크랑 임베디드 공부위주로 하였고 CCNA를 활용하여<br />
                서버를 구축이 가능하며 네트워크2급자격증, 정보처리산업기사,
                CCNA자격증을 취득하였고 더 많은 공부를 하기위해 <br />전공심화를
                선택하여 현재 명지전문대학교 전공심화에서 진로를 찾는 중 입니다.
              </p>
              <br />
              <h4>나의목표 및 향후계획</h4>
              <p class="text-grey">
                통신망에서 발생하는 각종 정보누출, 도청 ,정보변조의 공격과
                위협을 예방하고 대처하는 정보보안기사 자격증 획득입니다.
                <br />메모리 구조와 더불어 버퍼오버플로우 시스템에서 발생할 수
                있는 취약점을 생각하고 네트워크 공격의 경우 각각의 공격의
                <br />특징을 파악하고 대응 방안을 알아보고 간단한 정보보호
                개념부터 접근 통제 암호학을 공부합니다.
              </p>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <div class="text-center mt-4">
        <h1 class="text-red">List</h1>
        <div style="width: 120px; margin: 0 auto"></div>
      </div>
      <v-col cols="12" class="padd" id="List">
        <div class="first" id="project">
          <v-row>
            <v-col cols="12">
              <div class="child bgColor1">
                <v-icon color="#A7121D" x-large class="ml-3"
                  >fas fa-paper-plane</v-icon
                >
                <h3 class="white--text ml-3 mt-4">여행</h3>
                <p class="grey--text ml-3 mt-6">
                  나의 여행지 사진을 공유하고 <br />여행지를 추천한다.
                </p>
              </div>
              <div class="child bgColor2">
                <v-icon color="" x-large class="ml-3" dark
                  >fas fa-book-open</v-icon
                >
                <h3 class="white--text ml-3 mt-4">독서</h3>
                <p class="grey--text ml-3 mt-6">
                  독서활동을 추천하여<br />사람들과 공유한다.
                </p>
              </div>
              <div class="child bgColor1">
                <v-icon color="#A7121D" x-large class="ml-3"
                  >far fa-lightbulb</v-icon
                >
                <h3 class="white--text ml-3 mt-4">취미</h3>
                <p class="grey--text ml-3 mt-6">
                  나의 취미를 공유하고 <br />취미를 설명한다.
                </p>
              </div>
            </v-col>
          </v-row>
          <v-divider></v-divider>
        </div>
        <div class="text-center mt-4">
          <h1 class="text-red">Trip Photo</h1>
          <div style="width: 120px; margin: 0 auto"></div>
        </div>
      </v-col>
      <v-col cols="12" sm="12" id="Trip Photo">
        <div class="d-flex justify-center mb-6">
          <v-btn color="#FBDF7E" class="mr-2">전체</v-btn>

          <v-btn
            class="mr-2"
            variant="tonal"
            :href="'https://www.getyourguide.com/-l2713/?cmp=ga&cq_src=google_ads&cq_cmp=6656468135&cq_con=80468550433&cq_term=london%20tower%20bridge&cq_med=&cq_plac=&cq_net=s&cq_pos=&cq_plt=gp&campaign_id=6656468135&adgroup_id=80468550433&target_id=kwd-28351410&loc_physical_ms=2410&match_type=b&ad_id=628213216686&keyword=london%20tower%20bridge&ad_position=&feed_item_id=&placement=&device=c&partner_id=CD951&gclid=EAIaIQobChMI7Ya42cbp-gIVSGoqCh0ZjgxdEAAYASABEgL4yfD_BwE'"
            target="_blank"
          >
            <span>잉글랜드</span>
          </v-btn>

          <v-btn
            class="mr-2"
            variant="tonal"
            :href="'https://www.youtube.com/watch?v=CgUuPly_nuc'"
            target="_blank"
          >
            <span>이탈리아</span>
          </v-btn>
          <v-btn
            class="mr-2"
            variant="tonal"
            :href="'https://www.youtube.com/watch?v=b4cH7PF2yLY'"
            target="_blank"
          >
            <span>문수산</span>
          </v-btn>
          <v-btn
            class="mr-2"
            variant="tonal"
            :href="'https://www.youtube.com/watch?v=IAfuDVEko5s'"
            target="_blank"
          >
            <span>누메아</span>
          </v-btn>
        </div>
      </v-col>
      <v-col cols="12" class="imageHover">
        <div class="pre">
          <v-row class="fill-height" align="center" justify="center">
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="700" height="">
                <v-img src="m4.jpg" height="200px" cover> </v-img>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="700" height="">
                <v-img src="m2.jpg" height="200px" cover> </v-img>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="700" height="">
                <v-img src="h3.jpg" height="200px" cover> </v-img>
              </v-card>
            </v-col>
            <v-row>
              <v-col cols="12" sm="4">
                <v-card class="mw-auto" max-width="700" height="">
                  <v-img src="h4.jpg" height="200px" cover> </v-img>
                </v-card>
              </v-col>
              <v-col cols="12" sm="4">
                <v-card class="mw-auto" max-width="700" height="">
                  <v-img src="h5.jpg" height="200px" cover> </v-img>
                </v-card>
              </v-col>
              <v-col cols="12" sm="4">
                <v-card class="mw-auto" max-width="700" height="">
                  <v-img src="m8.jpg" height="200px" cover> </v-img>
                </v-card>
              </v-col>
            </v-row>
          </v-row>
        </div>
      </v-col>
      <v-col cols="12" sm="12">
        <div class="text-center mt-4">
          <h1 class="text-red">Best Trip</h1>
          <div style="width: 120px; margin: 0 auto"></div>
        </div>
        <div class="d-flex justify-center mb-6"></div>
      </v-col>
      <v-col cols="12" id="Best Trip">
        <div class="pre">
          <v-row>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="m4.jpg" height="200px" cover> </v-img>
                <v-card-title> 이탈리아 베네치아 </v-card-title>
                <v-card-subtitle class="text-green"
                  >By 2018 Italy | 08 09 best</v-card-subtitle
                >
                <v-card-text>
                  나의 여행지에서 첫번째인 베네치아를 소개합니다.<br />
                  그 중에 가장 인상 깊었던 배네치아 곤돌라 인데요!<br />
                  건물 색감이 정말 예뻐서 만족했지만 가격이 너무 비싼게<br />
                  단점으로 생각하지만 첫 여행지로 정말 추천하는 여행지입니다.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="m2.jpg" height="200px" cover> </v-img>
                <v-card-title> 문수산성 </v-card-title>
                <v-card-subtitle class="text-green"
                  >By 2022 Korea | 07 09 best</v-card-subtitle
                >
                <v-card-text>
                  나의 여행지에서 가장 만족한 두번째인 문수산성을 소개합니다.<br />
                  김포에서 가장 높은 산이며 조선시대의 역사가 살아있는 산이라고
                  <br />할 수 있고 가을에 다녀왓던 문수산성은 낙엽으로 덮여져
                  <br />있어 관경이 매우 아름다웠습니다.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="m5.jpg" height="200px" cover> </v-img>
                <v-card-title> 영국 타워브릿지 </v-card-title>
                <v-card-subtitle class="text-green"
                  >By 2016 England | 03 09 best</v-card-subtitle
                >
                <v-card-text>
                  나의 여행지에서 마지막 세번쨰인 영국 타워브리지를
                  소개합니다.<br />
                  빅벤과 함께 런던의 상징적인 건물로 알려져 있는 타워브릿지는
                  <br />템스강 남단의 강변 산책로를 따라 걷다 보면 전망대가
                  나오는데 <br />전망대에서 바라본 전경이 제일 기억에 남는다.
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <div class="text-center mt-4">
        <h1 class="text-red">Book</h1>
        <div style="width: 120px; margin: 0 auto"></div>
      </div>
      <v-col cols="12" id="Book">
        <div class="ols">
          <v-card class="rounded-xl mt-2">
            <v-row>
              <v-col cols="11" sm="4" align="center">
                <v-avatar size="370" tile>
                  <v-img src="q1.jpg"></v-img>
                </v-avatar>
              </v-col>
              <v-col cols="12" sm="8" class="px-10">
                <h1 class="grey--text">청춘서간</h1>
                <p class="grey--text">출간일:2020년 07월 10일 저자:이경교</p>
                <p class="text-yellow">★★★★★ 평가:9.5/10</p>

                <br />
                <h5 class="grey--text">
                  <h2 class="text-red">*책소개*</h2>
                  <br />
                  이경교 시인의 일상과 여행에서 삶을 투시하는 글들은 습관을 통해
                  감동을 기르는 방법에 대해 이야기한다.<br />
                  일상에서 그리고 여행지에서 문학과 예술, 역사와 철학을 넘나들며
                  탐구한 사유들을 시적 문장으로 엮었다.<br />
                  바슐라르, 릴케, 멜로니에서 부터 다산과 정몽주, 이황 등
                  동서양을 넘나드는 감동과 상상력의 원천을 찾아나가고<br />
                  이 책은 이 땅의 청춘들에게 주는 편지이자 우리 모두의
                  '어둠속에서 마주하는 빛의 기록' 이다. <br /><br />
                  <h2 class="text-red">*독후감*</h2>
                  <br />
                  청춘의 시기는 누구에게나 고통스럽다. 그건 꿈이 크기 때문이기도
                  하지만, 기성 인식을 향한 거부감 탓이기도 하고<br />
                  청년들이 살만한 세상을 꿈꾸듯이 나는 그들이 더 강인하게
                  성장하기를 바라고 강인함은 울분을 통해 길러지는 것이 아니라<br />
                  꿈을 꾸고 상상하는 순간 성장하고 4월이란 계절은 모순적인
                  계절이고 인생 또한 다르지 않다고 생각하여 즐거운 잔치엔 언제나
                  취객이<br />
                  등장하기 마련이며 좋은 일엔 항상 훼방 꾼이 길을 막는 현상이
                  일어나고 기쁨이 오히려 슬픔의 빌미가 되어, 불행이 때론 행복의
                  발판으로 바뀌는게<br />
                  인생이라고 생각하고 철학을 넘나들며 탐구한 시적 문장으로
                  엮어서 우리들에게 간편하게 설명하여 나타낸다.
                </h5>
              </v-col>
            </v-row>
          </v-card>
        </div>
      </v-col>
      <div class="text-center mt-6">
        <h1 class="text-red">Hobbie & Activity</h1>
        <div style="width: 120px; margin: 0 auto"></div>
      </div>
      <div class="d-flex justify-center mb-6"></div>
      <v-col cols="12" id="hobbie">
        <div class="hire">
          <v-row>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="m10.jpg" height="200px" cover> </v-img>
                <v-card-title class="text-blue"> LOL</v-card-title>

                <v-card-text>
                  저의 시간이 남을떄 게임을 자주 하는 편입니다!<br />
                  리그오브레전드 게임은 5대5 각종 포지션별로 라인을 정해서
                  상대를<br />
                  제압하는 게임으로 친구들과 같이 게임할때 가장 즐거운
                  게임이라고 <br />생각하고 모바일 및 각종 기기로도 게임
                  플레이가 가능합니다.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="m7.jpg" height="200px" cover> </v-img>
                <v-card-title class="text-blue"> 볼링 </v-card-title>

                <v-card-text>
                  볼링은 스포츠 게임으로 불리고 12개의 핀을 공을 날려서
                  쓰러트리는 게임으로 점수를 가장 많이 쌓으면 승리합니다. 저는
                  학교 다닐떄부터 친구들과 볼링을 자주 치러 다녔고 현재는
                  친구들과 즐겁게 즐기는 <br />스포츠중 하나로 스트라이크를 칠때
                  가장 만족감을 느낀다.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="m9.jpg" height="200px" cover> </v-img>
                <v-card-title class="text-blue"> 영화 </v-card-title>

                <v-card-text>
                  저는 주말에 여가생활을 자주 하는 편인데 그 중에서 영화를
                  <br />자주 보러 다니고 가장 인상깊었던 영화는
                  어바웃타임인데<br />
                  이 영화를 보면서 감동을 느꼈기 보다는 현재 무의미하게<br />
                  시간을 보냈던 제 시간에 살아있는 생동감을 안겨준 영화였습니다.
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="v3.jpg" height="200px" cover> </v-img>
                <v-card-title class="text-blue"> 리눅스 </v-card-title>

                <v-card-text>
                  저는 전 학교에서 공식적으로 물리 주소 확장 기능을 가진<br />
                  아키텍처로 CentOs를 이용하여 레드햇과 같은 기능을 가진<br />
                  무료 베포만을 이용하여 서버를 구축하여 간단한
                  httped서비스를<br />
                  시작하여 DB를 확인하여 Web html의 작동을 확인시키고<br />
                  외부에서도 접속이 가능하도록 방화벽을 확인함.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="v6.jpg" height="200px" cover> </v-img>
                <v-card-title class="text-blue"> 아두이노 휴지통 </v-card-title>

                <v-card-text>
                  전 학교에서 과제로 아두이노 우노를 다운받아서 초음파 센서
                  아두이노 우노, 브래드보드, 서브모터를 연결하고 프로그램
                  소스코드를 <br />작성한 뒤 아두이노 업로드를 통하여 작품을
                  동작시켰다.<br />
                  처음으로 작품을 만들어 본 것으로 나의 기억에는 처음으로 만든
                  <br />의미있는 작품으로 기억에 남아서 포트폴리오에 작성했다.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="v11.jpg" height="200px" cover> </v-img>
                <v-card-title class="text-blue">
                  Cisco Paket Tracer
                </v-card-title>

                <v-card-text>
                  특정 네트워크 장비의 설정을 건드리는 방법은 장비가 없이는
                  실습을 해볼수가 없어서 Cisco에서는 실습을 할 수 있는 환경이
                  적용되어 있고 라우터, 스위치 관리 명령어를 직접 쳐보면서
                  나만의 서버를 구축하고 실행하여 pc와 라우트와 서버간의
                  정상적으로 작동하는 것을 <br />확인하여서 실무 경험에 중요한
                  서버 구축을 하여 도움이 되었다.
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </div>
      </v-col>
    </v-container>

    <FooterView />
  </v-app>
</template>

<script>
import { defineComponent } from "vue";
import NavBar from "../components/NavBar.vue";
import FooterView from "../components/FooterView.vue";

// Components
//import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: "HomeView",
  setup() {
    return {
      slider2: 50,

      items: [
        {
          img: "i3.jpg",
        },
        {
          img: "i4.jpg",
        },
        {
          img: "i5.jpg",
        },
        {
          img: "i6.jpeg",
        },
        {
          img: "i9.jpg",
        },
        {
          img: "i8.jpg",
        },
      ],
    };
  },
  components: {
    NavBar,
    FooterView,
  },
});
</script>
<style scoped>
.v-container {
  padding: 16px 0 16px 0;
}

.head {
  position: relative;
  text-align: center;
  padding: 12px;
  margin-bottom: 6px;
  height: 400px;
  width: 100%;
  color: white;
}
.head:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, 6deg);
}
.head:after {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, -6deg);
}
.egg {
  display: block;
  margin-left: 100px;
  margin-top: 50px;
  width: 356px;
  height: 300px;
  background-color: #fbdf7e;
  border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}
.first {
  width: 100%;
  height: 280px;
  text-align: center;
  padding: 2rem 2rem;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: center;
  margin-right: 8px;
}
.imgHover {
  padding: 0 200px;
}
.pre {
  width: 100%;
  height: 500px;
  text-align: center;
  padding: 0 200px;
  background-color: #f5f5f5;
}
.hire {
  width: 100%;
  height: 800px;
  text-align: center;
  padding: 0 200px;
  background-color: #f5f5f5;
}
.bgColor1 {
  background-color: greenyellow;
}
.bgColor2 {
  background-color: white;
}
.ols {
  width: 100%;
  height: 500px;
  text-align: center;
  padding: 0 200px;
  background-color: #f5f5f5;
}
</style>
 