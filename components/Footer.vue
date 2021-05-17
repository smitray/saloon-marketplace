<template>
  <footer class="footer">
    <div
      class="
        container container--full container--wr container--ovh container--rel
        footer--top
      "
    ></div>
    <div
      class="container container--full container--wr container--rel footer--wr"
    >
      <div class="container container--block container--wr container--rel">
        <ul class="footer__social">
          <li>
            <a href="#"><img src="~/assets/img/Social-1.png" alt="" /></a>
          </li>
          <li>
            <a href="#"><img src="~/assets/img/Social-2.png" alt="" /></a>
          </li>
          <li>
            <a href="#"><img src="~/assets/img/Social-3.png" alt="" /></a>
          </li>
        </ul>
        <ul class="footer__links">
          <li><a href="#">Dazlure</a></li>
          <li><a href="#"> contact us</a></li>
          <li><a href="#">privacy policy</a></li>
          <li><a href="#">service agreement</a></li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<style lang="postcss" scoped>
.footer {
  &--top {
    bg: url('~/assets/img/footer__top.svg') no-repeat;
    background-size: 100% 100%;
    h: 125px;
    w: 102%;
    ml: -1px;

    @media only map(breakpoints, phone) {
      display: none;
    }
  }
  &--wr {
    bg: map(colors, dark);
    margin-top: -4px;

    @media only map(breakpoints, phone) {
      &:before {
        bg: url('~/assets/img/footer-top-mobile.svg') no-repeat;
        content: '';
        w: 100%;
        position: absolute;
        height: 60px;
        top: -59px;
        left: 0;
        background-size: 100% 100%;
      }
    }
  }

  &__links {
    margin: 3rem * 6rem;
    padding: 0;
    list-style: none;
    overflow: hidden;

    li {
      float: left;
      m: 1rem 8rem;

      a {
        text-decoration: none;
        color: #fff;
        text-transform: capitalize;
        fw: 800;
      }

      @media only map(breakpoints, phone) {
        text-align: center;
        width: 100%;
        float: none;
        margin: * 0;

        a {
          display: block;
        }
      }

      &:last-child {
        mr: 0;
      }

      &:first-child {
        ml: 0;
        mt: 0;

        @media only map(breakpoints, phone) {
          display: none;
        }

        a {
          background: rgba(254, 80, 152, 1);
          background: -moz-linear-gradient(
            left,
            rgba(254, 80, 152, 1) 0%,
            rgba(254, 60, 60, 1) 100%
          );
          background: -webkit-gradient(
            left top,
            right top,
            color-stop(0%, rgba(254, 80, 152, 1)),
            color-stop(100%, rgba(254, 60, 60, 1))
          );
          background: -webkit-linear-gradient(
            left,
            rgba(254, 80, 152, 1) 0%,
            rgba(254, 60, 60, 1) 100%
          );
          background: -o-linear-gradient(
            left,
            rgba(254, 80, 152, 1) 0%,
            rgba(254, 60, 60, 1) 100%
          );
          background: -ms-linear-gradient(
            left,
            rgba(254, 80, 152, 1) 0%,
            rgba(254, 60, 60, 1) 100%
          );
          background: linear-gradient(
            to right,
            rgba(254, 80, 152, 1) 0%,
            rgba(254, 60, 60, 1) 100%
          );
          filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#fe5098', endColorstr='#fe3c3c', GradientType=1 );
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
          fz: 3.2rem;
          letter-spacing: 1rem;
        }
      }
    }
  }

  &__social {
    margin: 0;
    padding: 0;
    list-style: none;
    w: 31%;
    m: -45px auto *;
    overflow: hidden;
    display: flex;

    @media only map(breakpoints, phone) {
      width: 50%;
      margin-top: -20px;

      li {
        a {
          w: 50%;
        }
      }
    }

    li {
      flex: 1;

      a {
        display: block;
        text-decoration: none;
        width: 35%;
        margin: 0 auto;

        img {
          w: 100%;
          height: auto;
        }
      }

      &:first-child {
        ml: 0;
      }

      &:last-child {
        mr: 0;
      }
    }
  }
}
</style>
