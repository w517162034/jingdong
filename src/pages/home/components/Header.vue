<template>
  <header id="top">
    <div class="topList">
      <!--切换地址-->
      <div class="address">
        <span>北京</span>
        <div class="addressList">
          <ul>
            <li class="province"><a href="javascript:" class="add_checked">北京</a></li>
            <li class="province"><a href="javascript:">上海</a></li>
            <li class="province"><a href="javascript:">天津</a></li>
            <li class="province"><a href="javascript:">重庆</a></li>
            <li class="province"><a href="javascript:">河北</a></li>
            <li class="province"><a href="javascript:">山西</a></li>
            <li class="province"><a href="javascript:">河南</a></li>
            <li class="province"><a href="javascript:">辽宁</a></li>
            <li class="province"><a href="javascript:">吉林</a></li>
            <li class="province"><a href="javascript:">黑龙江</a></li>
            <li class="province"><a href="javascript:">内蒙古</a></li>
            <li class="province"><a href="javascript:">江苏</a></li>
            <li class="province"><a href="javascript:">山东</a></li>
            <li class="province"><a href="javascript:">安徽</a></li>
            <li class="province"><a href="javascript:">浙江</a></li>
            <li class="province"><a href="javascript:">福建</a></li>
            <li class="province"><a href="javascript:">湖北</a></li>
            <li class="province"><a href="javascript:">湖南</a></li>
            <li class="province"><a href="javascript:">广东</a></li>
            <li class="province"><a href="javascript:">广西</a></li>
            <li class="province"><a href="javascript:">江西</a></li>
            <li class="province"><a href="javascript:">四川</a></li>
            <li class="province"><a href="javascript:">海南</a></li>
            <li class="province"><a href="javascript:">贵州</a></li>
            <li class="province"><a href="javascript:">云南</a></li>
            <li class="province"><a href="javascript:">西藏</a></li>
            <li class="province"><a href="javascript:">陕西</a></li>
            <li class="province"><a href="javascript:">甘肃</a></li>
            <li class="province"><a href="javascript:">青海</a></li>
            <li class="province"><a href="javascript:">宁夏</a></li>
            <li class="province"><a href="javascript:">新疆</a></li>
            <li class="province"><a href="javascript:">港澳</a></li>
            <li class="province"><a href="javascript:">台湾</a></li>
            <li class="province"><a href="javascript:">钓鱼岛</a></li>
            <li class="province"><a href="javascript:">海外</a></li></ul>
        </div>
      </div>
      <!--切换地址结束-->
      <!--顶部右边列表-->
      <ul class="topNav">
        <li class="rabbit hover"><a href="javascript:">兔牙印尼玛<img src="/static/index_images/plus.png" alt="" style="vertical-align: middle; margin-left: 5px;"/></a>&nbsp;&nbsp;|&nbsp;
          <div class="navShow user">
            <div class="touxiang">
              <img src="/static/index_images/touxiang.jpg" />
                <div class="touxiang_right">
                  <p><span>退出</span></p>
                  <p>您可享银牌特惠，开通PLUS></p>
                </div>
            </div>
            <hr />
            <div class="userScroll">
              <span class="turnLeft">&lt;</span>
              <span class="turnRight">&gt;</span>
              <div class="scroll">
                <div class="dls">
                  <dl>
                    <dt><img src="/static/index_images/free.png"/></dt>
                    <dd class="title">免费试用</dd>
                  </dl>
                  <dl>
                    <dt><img src="/static/index_images/service.png"/></dt>
                    <dd class="title">售后服务</dd>
                  </dl>
                  <dl>
                    <dt><img src="/static/index_images/bouns.png"/></dt>
                    <dd class="title">评价奖励</dd>
                  </dl>
                  <dl>
                    <dt><img src="/static/index_images/privilige.png"/></dt>
                    <dd class="title">会员特权</dd>
                  </dl>
                  <dl>
                    <dt><img src="/static/index_images/birth.png" /></dt>
                    <dd class='title'>生日礼包</dd>
                  </dl>
                  <dl>
                    <dt><img src="/static/index_images/personal.png" /></dt>
                    <dd class='title'>专机服务</dd>
                  </dl>
                  <dl>
                    <dt><img src="/static/index_images/high.png" /></dt>
                    <dd class='title'>贵宾专线</dd>
                  </dl>
                  <dl>
                    <dt><img src="/static/index_images/after.png" /></dt>
                    <dd class='title'>售后券</dd>
                  </dl>
                </div>
              </div>
            </div>
          </div>
        </li>
        <li><a href="javascript:">我的订单</a>&nbsp;&nbsp;|&nbsp;</li>
        <li class="myDong hover">
          <a href="javascript:">我的京东</a>&nbsp;&nbsp;|&nbsp;
          <div class="navShow">
            <div class="dong_top">
              <p><span>待处理订单</span> <em>消息 <i>16</i></em></p>
              <p><span>降价商品 <i>2</i></span><em> 返修退换货</em></p>
              <p><span>我的问答</span> <em>我的关注</em></p>
            </div>
            <hr />
            <div class="dong_bottom">
              <p><span>我的京豆</span> <em>我的白条</em></p>
              <p><span>我的优惠券</span> <em>我的理财</em></p>
            </div>
          </div>
        </li>
        <li><a href="javascript:">京东会员</a>&nbsp;&nbsp;|&nbsp;</li>
        <li><a href="javascript:">企业采购</a>&nbsp;&nbsp;|&nbsp;</li>
        <li><a href="javascript:">客户服务</a>&nbsp;&nbsp;|&nbsp;</li>
        <li><a href="javascript:">网站导航</a>&nbsp;&nbsp;|&nbsp;</li>
        <li><a href="javascript:">手机京东</a></li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="scss" scoped>
  header {
    height :30px;
    background: rgb(227,228,230);
    font-size: 12px;
    line-height: 30px;
    color: rgb(143,143,143);
    position: relative;
    .topList{
      width: 990px;
      height: 100%;
      margin-left: 280px;
      a{
        font-size: 12px;
        height: 100%;
      }
      /* 顶部定位区域 */
      .address{
        position: relative;
        /* 顶部定位区域滑过样式 */
        &:hover .addressList{
          display: block;
        }
        &:hover span{
          border: 1px solid rgb(200,200,200);
          border-bottom: 1px solid #fff;
          position: relative;
          z-index: 100;
          background-color: #fff;
      }
        >span{
          width: 70px;
          height: 30px;
          background: url("/static/index_images/address.png") no-repeat 6px center;
          background-size: 20px 17px;
          padding-left: 27px;
          color: rgb(143,143,143);
          float: left;
          border: 1px solid rgba(227,228,230,0);
        }
        .addressList{
          width: 350px;
          border: 1px solid rgb(224,224,224);
          display: none;
          padding: 10px 15px;
          position: absolute;
          left: 0;
          top: 29px;
          z-index: 1;
          box-shadow: 0 0 5px #ddd;
          background: #fff;
          li{
            float: left;
            width: 70px;
            height: 25px;
            line-height: 25px;
            text-align: left;
            margin: 1px 0;
            a{
              padding: 0 10px;
              font-size: 10px;
              &:hover{
                color: rgb(221,12,44);
              }
              .add_checked{
                background: rgb(221,12,44);
                color: #fff;
              }
            }
          }
        }
      }
    }
    /* 顶部右边选项列表 */
    .topNav{
        float: right;
        >li {
          float: left;
        }
        li{
          &:nth-child(1) a img{
            width: 40px;
            height: 16px;
          }
          &:nth-child(1) a,
          &:nth-child(3) a,
          &:nth-child(6) a,
          &:nth-child(7) a{
            background: url("/static/index_images/down.png") no-repeat right center;
            background-size: 15px 15px;
          }
          a{
            height: 30px;
            padding: 0 15px;
            border: 1px solid rgba(227,228,230,0);
            &:hover{
              color: rgb(221,12,44);}
            }
          }
      /* 顶部右边用户 */
      .user{
        position: absolute;
        width: 290px;
        border: 1px solid rgb(224,224,224);
        box-shadow: 0 0 5px #ddd;
      }
      .navShow{
        .touxiang {
          padding: 10px 15px;
          img{
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: inline-block;
          }
          .touxiang_right{
            float: right;
            p{
              &:nth-child(1){
                background: url("/static/index_images/plus.png") no-repeat left center;
                padding-left: 150px;
              }
            }
          }
        }
        .userScroll{
          position: relative;
          .scroll{
            position: relative;
            overflow: hidden;
            height: 80px;
            margin: 15px auto;
            width: 220px;
            .dls{
              position: absolute;
              width: 1000%;
              margin: 0 auto;
              dl{
                float: left;
                width: 60px;
                padding: 0 5px;
                margin-right: 6px;
                dt{
                  width: 60px;
                  img{
                    width: 50%;
                    height: 50%;
                    margin:10% 25%;
                  }
                }
                dd{
                  line-height: 35px;
                  text-align: center;
                  cursor: pointer;
                  &:hover{
                    color:rgb(221,12,44);
                  }
                }
              }
            }
          }
          span{
            display: inline-block;
            position: absolute;
            font-size: 30px;
            top: 15px;
            cursor: pointer;
            color: #ccc;
            font-style: normal;
            &:hover{
              color:rgb(221,12,44);
            }
          }
          .turnLeft{
            left: 2px;
          }
          .turnRight{
            right: 2px;
          }
        }
      }
      /* 顶部列表右边我的京东 */
      .myDong{
        .navShow{
          width: 250px;
          .dong_top
          .dong_bottom{
            padding: 10px 15px;
          }
        }
        em{
          display: inline-block;
          float: right;
          text-align: left;
          width: 100px;
        }
        em
        span{
          &:hover{
            color: rgb(221,12,44);
            cursor: pointer;
          }
        }
        i{
          color: rgb(221,12,44);
        }
      }
    }
  }
</style>
