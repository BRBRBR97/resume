<template>
  <div id="app">
    <div class="content">
      <div class="resume">
        <div class="nameArea">
          <strong>김보람</strong>
          <span>웹퍼블리셔 + 프론트엔드개발</span>
          <p> 플립커뮤니케이션즈에서 프론트개발자 구인공고를 보고 많이 설레였습니다.<br>
            다양한 프로젝트를 경험할 수 있는 웹에이전시면서 업계에서 오래도록 메인저자리를 지키는 회사라 들었기 때문에 혹시나 저에게도 기회가 올까 하는 설레임반과 망설임반으로 이력서를 다듬어보았습니다.<br>
            컴퓨터에 관심이 없던 저에게 이전에 근무했던 회사에서 모든 업무를 인터넷 웹을 통해 처리하는것을 보고 놀랐습니다. 매우 편리했지만 이미 만들어진 웹을 사용만 할려고하니 불편한점이 한두가지가 아니라서 몇일을 구글링하며 어에게 맞게 수정하고 그게 작동했을때 신기하고 재밌었습니다. 그뒤로 몇번의 비슷한 경험을 통해 제가 어떤것을 할때 잘집중하는지 그리고 하고싶은것은 무엇인지 고민하게 되었고 웹퍼블리싱과 프론트엔드개발이라는 분양를 알게되어 관심을 갖고 공부하게 되었습니다.<br>
            학원, 모임등 여러가지를 해보고 싶었으나 코로나로 인해 오프라인으로 진행하는곳이 없어 온라인 패스트캠퍼스에서 웹퍼블리싱및 프론트엔드개발에대해 스스로 공부하고 커뮤니티에서 활동하며 지식을 쌓고있습니다.<br>
            신입으로 시작하기 매우 힘든시기에 그것도 메이저웹에이전시는 더 힘들거라 생각하고있습니다. 기회가 저에게 온다면 자만하지 않고 늘 배우는 프론트개발자가 될거라 약속드리며 플립커뮤니케이션즈에 지원합니다.</p>
        </div>

        <div class="cont">
          <div class="titArea">
            <h2 class="tit">경력</h2>
          </div>
          <ul class="yearList">
            <li>
              <div class="year">2018</div>
              <div class="desc">
                <strong>회계팀</strong>
                <span>글라스.../대구</span>
                <p>회계 관련 업무</p>
              </div>
            </li>
            <li>
              <div class="year">2019</div>
              <div class="desc">
                <strong>포워딩 / 수입(Import)부서</strong>
                <span>SG국제운송/대구</span>
                <p>수입 통관 관세 관련 업무</p>
              </div>
            </li>
          </ul>
        </div>

        <div class="cont">
          <div class="titArea">
            <h2 class="tit">자격증</h2>
          </div>
          <ul class="yearList">
            <li>
              <div class="year">2004</div>
              <div class="desc">
                <strong>워드프로세서 2급</strong>
                <span>대한상공회의소 주관</span>
              </div>
            </li>
            <li>
              <div class="year">2015</div>
              <div class="desc">
                <strong>Microsoft Office Specialist 파워포인트 2010</strong>
                <span>마이크로소프트 주관</span>
              </div>
            </li>
          </ul>
        </div>

        <div class="cont">
          <div class="titArea">
            <h2 class="tit">학력</h2>
          </div>
          <ul class="yearList">
            <li>
              <div class="year">2012</div>
              <div class="desc">
                <strong>고등학교</strong>
                <span>중산외국어고등학교 영어과졸업</span>
              </div>
            </li>
            <li>
              <div class="year">2016</div>
              <div class="desc">
                <strong>대학교 경제학사,경영학사</strong>
                <span>대구한의대학교 통상경제학부/세무회계,국제통상전공졸업</span>
              </div>
            </li>
          </ul>
        </div>

        <div class="cont">
          <div class="titArea">
            <h2 class="tit">스터디</h2>
          </div>
          <ul class="yearList">
            <li>
              <div class="year">2021</div>
              <div class="desc">
                <strong>수강완료</strong>
                <span>HTML/CSS, JavaScript 올인원 패키지 Online</span>
              </div>
            </li>
            <li>
              <div class="year">2021</div>
              <div class="desc">
                <strong>수강완료</strong>
                <span>프론트엔드 개발 올인원 패키지 with React</span>
              </div>
            </li>
          </ul>
        </div>
      </div>

      <div class="personal">
        <div class="photo">
          <img :src="require('./assets/images/br.jpg')" alt="BR">
        </div>
        <div class="cont">
          <div class="titArea">
            <h2 class="tit">연락처</h2>
          </div>
          <ul class="icoList">
            <li class="phone">
              <strong>휴대폰</strong>
              <span>010-7271-9397</span>
            </li>
            <li class="email">
              <strong>Email</strong>
              <span>treasurebr9397@gmail.com</span>
            </li>
            <li class="address">
              <strong>주소</strong>
              <span>충청북도 충주시</span>
            </li>
          </ul>
        </div>

        <div class="cont">
          <div class="titArea">
            <h2 class="tit">성격</h2>
          </div>
          <ul>
            <li>꼼꼼함</li>
            <li>본인을 잘 아는</li>
            <li>성실함</li>
            <li>차분한</li>
          </ul>
        </div>

        <div class="cont">
          <div class="titArea">
            <h2 class="tit">능력</h2>
          </div>
          <div class="graph">
            <ul>
              <li><span class="g">HTML</span><span class="g_bar" :class="{'active': bar1}" :style="`width:${bar1 ? 50 : 0}%`"><span></span></span></li>
              <li><span class="g">CSS</span><span class="g_bar" :class="{'active': bar2}" :style="`width:${bar2 ? 50 : 0}%`"><span></span></span></li>
              <li><span class="g">JS</span><span class="g_bar" :class="{'active': bar3}" :style="`width:${bar3 ? 20 : 0}%`"><span></span></span></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      bar1: false,
      bar2: false,
      bar3: false
    }
  },
  mounted() {
    setTimeout(() => {
      this.bar1 = true
    }, 1000)
    setTimeout(() => {
      this.bar2 = true
    }, 2000)
    setTimeout(() => {
      this.bar3 = true
    }, 3000)
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
}
</style>
