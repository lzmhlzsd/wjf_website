<style lang="scss">
.page-index {
  height: 100%;
  a:hover {
    text-decoration: none;
  }
  .r {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100%;
    color: #fff;
  }
}
.container1 {
  height: 35%;
  .left {
    width: 50%;
    height: 100%;
    padding: 10px 5px 10px 10px;
    .r0 {
      background: rgb(249, 189, 37);
      border-radius: 20px 0 0 0;
    }
  }
  .right {
    width: 50%;
    height: 100%;
    .top {
      height: 50%;
      padding: 10px 10px 5px 5px;
      .r1 {
        background: rgb(83, 206, 250);
      }
    }
    .bottom {
      height: 50%;
      padding: 5px 10px 10px 5px;
      .r2 {
        background: rgb(4, 187, 19);
        border-radius: 0 0 20px 0;
      }
    }
  }
}
.container2 {
  height: 30%;
  padding: 0 10px 10px;
  .r3 {
    // background: rgb(23, 222, 249);
    background: url('~@/assets/2084.jpeg') no-repeat;
    background-size: 100% 100%;
  }
}
.container3 {
  height: 35%;
  > .left {
    width: 50%;
    height: 100%;
    .top {
      height: 50%;
      .left {
         width: 50%;
         height: 100%;
         padding: 0 5px 5px 10px;
        .r4 {
          background: rgb(117, 7, 196);
          border-radius: 20px 0 0 0;
        }
      }
      .right {
         width: 50%;
         height: 100%;
         padding: 0 5px 5px 5px;
        .r5 {
          background: rgb(4, 187, 19);
        }
      }
    }
    .bottom {
      height: 50%;
      padding: 5px 5px 10px 10px;
      .r6 {
        background: rgb(225, 104, 29);
      }
    }
  }
  > .right {
    width: 50%;
    height: 100%;
    padding: 0 10px 10px 5px;
    .r7 {
      background: rgb(210, 203, 7);
      border-radius: 0 0 20px 0;
    }
  }
}
</style>

<template>
  <div class="page-index">
    <div class="container1 clearfix">
      <div class="left fl">
        <a href="http://www.ntmaimeng.com/f/UWqF3n"><div class="r0 r">监督取证</div></a>
      </div>
      <div class="right fl">
        <div class="top">
          <a href="http://www.ntmaimeng.com/f/Pz6M4i"><div class="r1 r">人员点位</div></a>
        </div>
        <div class="bottom">
          <a href="http://www.ntmaimeng.com/f/1BHTx0"><div class="r2 r">销售话术</div></a>
        </div>
      </div>
    </div>
    <div class="container2">
      <div class="r3 r"></div>
    </div>
    <div class="container3 clearfix">
      <div class="left fl">
        <div class="top clearfix">
          <div class="left fl">
            <a href="https://biaodan100.com/web/formview/5d711021fc918f192e994b13"><div class="r4 r">考勤签到</div></a>
          </div>
          <div class="right fl">
            <a href="http://www.ntmaimeng.com/f/1UOHg3"><div class="r5 r">有话要说</div></a>
          </div>
        </div>
        <div class="bottom">
          <a href="http://www.ntmaimeng.com/f/hzA7qO"><div class="r6 r">新入网登记</div></a>
        </div>
      </div>
      <div class="right fl">
        <a href="http://www.ntmaimeng.com/f/khrSUa"><div class="r7 r">联系我们</div></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>