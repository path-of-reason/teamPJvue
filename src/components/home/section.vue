<template>
  <section>
    <!--추천친구-->
    <header>
      <figure>
        <img
          src="https://media.bunjang.co.kr/product/145752141_1_1624871282_w360.jpg"
          alt="python" />
        <figcaption>python</figcaption>
      </figure>
      <figure>
        <img
          src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbEYCwb%2FbtqBg8I1MMT%2FuapMAHKo0hQ47s8yf1epsk%2Fimg.jpg"
          alt="java" />
        <figcaption>java</figcaption>
      </figure>
      <figure>
        <img
          src="https://www.urbanbrush.net/web/wp-content/uploads/edd/2020/02/urbanbrush-20200211141401425142.jpg"
          alt="clojure" />
        <figcaption>clojure</figcaption>
      </figure>
      <figure>
        <img
          src="data:image/png;base64,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"
          alt="nodejs" />
        <figcaption>nodejs</figcaption>
      </figure>
      <figure>
        <img
          src="https://cdn.bokjitimes.com/news/photo/201807/19905_13761_914.jpg"
          alt="vue" />
        <figcaption>vue</figcaption>
      </figure>
      <figure>
        <img
          src="https://img.hankyung.com/photo/201907/AA.19998517.1.jpg"
          alt="spring" />
        <figcaption>spring</figcaption>
      </figure>
    </header>
    <hr />
    <!--컨텐츠-->
    <article>
      <div>
        <img
          class="user-img float"
          src="https://media.bunjang.co.kr/product/145752141_1_1624871282_w360.jpg"
          alt="python" />
        <div class="user-id-config">
          <span
            class="user-id left">python</span>
          <i class="fi-rr-menu-dots right"></i>
        </div>
      </div>
      <img
        class="content-img"
        src="https://cdn.pixabay.com/photo/2019/06/06/13/36/italy-4256017_960_720.jpg"
        alt="python_content" />
      <div class="content-icon">
        <i class="fi-rr-thumbs-up left"></i>
        <i class="fi-rr-comment left"></i>
        <i class="fi-rr-paper-plane left"></i>
        <i class="fi-rr-bookmark right"></i>
      </div>
      <div
        class="content-likes"
        style="font-weight: bold; padding-bottom: 5px">
        530 likes
      </div>
      <div
        class="comment-user-id"
        style="font-weight: bold; padding-bottom: 8px;">
        python
      </div>
      <div
        class="comment"
        style="padding-bottom: 5px">
        이번 여행은 유럽에... <span style="color:gray;">more</span>
      </div>
      <div style="color:gray;">
        View all comments
      </div>
      <div><span style="color:gray;">1 day ago</span></div>
    </article>
    <!--컨텐츠-->
    <br />
    <article>
      <div>
        <img
          class="user-img float"
          src="https://media.bunjang.co.kr/product/145752141_1_1624871282_w360.jpg"
          alt="python" />
        <div class="user-id-config">
          <span
            class="user-id left">python</span>
          <i class="fi-rr-menu-dots right"></i>
        </div>
      </div>
      <img
        class="content-img"
        src="https://cdn.pixabay.com/photo/2019/06/06/13/36/italy-4256017_960_720.jpg"
        alt="python_content" />
      <div class="content-icon">
        <i class="fi-rr-thumbs-up left"></i>
        <i class="fi-rr-comment left"></i>
        <i class="fi-rr-paper-plane left"></i>
        <i class="fi-rr-bookmark right"></i>
      </div>
      <div
        class="content-likes"
        style="font-weight: bold; padding-bottom: 5px">
        530 likes
      </div>
      <div
        class="comment-user-id"
        style="font-weight: bold; padding-bottom: 8px;">
        python
      </div>
      <div
        class="comment"
        style="padding-bottom: 5px">
        이번 여행은 유럽에... <span style="color:gray;">more</span>
      </div>
      <div style="color:gray;">
        View all comments
      </div>
      <div><span style="color:gray;">1 day ago</span></div>
    </article>
    <br />
    <!--컨텐츠-->
    <article>
      <div>
        <img
          class="user-img float"
          src="https://media.bunjang.co.kr/product/145752141_1_1624871282_w360.jpg"
          alt="python" />
        <div class="user-id-config">
          <span
            class="user-id left">python</span>
          <i class="fi-rr-menu-dots right"></i>
        </div>
      </div>
      <img
        class="content-img"
        src="https://cdn.pixabay.com/photo/2019/06/06/13/36/italy-4256017_960_720.jpg"
        alt="python_content" />
      <div class="content-icon">
        <i class="fi-rr-thumbs-up left"></i>
        <i class="fi-rr-comment left"></i>
        <i class="fi-rr-paper-plane left"></i>
        <i class="fi-rr-bookmark right"></i>
      </div>
      <div
        class="content-likes"
        style="font-weight: bold; padding-bottom: 5px;">
        530 likes
      </div>
      <div
        class="comment-user-id"
        style="font-weight: bold; padding-bottom: 8px;">
        python
      </div>
      <div
        class="comment"
        style="padding-bottom: 5px">
        이번 여행은 유럽에... <span style="color:gray;">more</span>
      </div>
      <div style="color:gray;">
        View all comments
      </div>
      <div><span style="color:gray;">1 day ago</span></div>
    </article>
  </section>
</template>

<script>
export default {
  name: "Section"
}
</script>

<style lang="scss" scoped>
@import url('https://cdn-uicons.flaticon.com/uicons-regular-rounded/css/uicons-regular-rounded.css');

section {
  padding: 10px;
  height: 520px;
  //스크롤바 없에기
  white-space: nowrap;
  overflow-x: auto;
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
  &::-webkit-scrollbar {
    display: none; /* Chrome, Safari, Opera*/
  }
  header { //추천친구
    height: 90px;
    //스크롤바 없에기
    white-space: nowrap;
    overflow-x: auto;
    -ms-overflow-style: none; /* IE and Edge */
    scrollbar-width: none; /* Firefox */
    &::-webkit-scrollbar {
      display: none; /* Chrome, Safari, Opera*/
    }
    figure { //이미지부모
      display: inline-block;
      margin: 0;
      padding-right: 6px;
      img { //이미지
        display: inline-block;
        border-radius: 40%;
        width: 60px;
        height: 60px;
        margin-right: 5px;
      }
      figcaption { //이미지 캡션
        text-align: center;
        padding-right: 5px;
        color: gray;
      }
    }
  }
  article { //게시물
    .user-img { //작성자 이미지
      border-radius: 40%;
      width: 30px;
      height: 30px;
      margin-right: 10px;
    }
    div { //float 해제
      clear: both;
      .user-id-config{
        display: inline-block;
        width: 88%;
        padding-top: 3px;
      }
    }
    .content-img { //게시물 이미지
      display: block;
      width: 340px;
      height: 240px;
      padding-top: 10px;
      padding-bottom: 10px;
    }
    i { //아이콘
      font-size: 110%;
      padding-bottom: 5px;
    }
  }
}
.float { //사용자 이미지
  float: left;
}
.left { //float 왼쪽정렬
  float: left;
  padding-right: 18px;
}
.right { //float 오른쪽정렬
  float: right;
  padding-left: 18px;
}
</style>