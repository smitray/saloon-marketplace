<template>
  <section
    class="
      container container--full container--wr container--ovh container--rel
      banner
    "
  >
    <img src="~/assets/img/banner-min.png" alt="" class="above-mobile" />
    <img src="~/assets/img/banner_image-min.jpg" alt="" class="on-mobile" />
    <div class="banner__content">
      <div class="banner__content--wr">
        <div class="banner__logo">
          <router-link :to="{ name: 'index' }">dazlure</router-link>
        </div>
        <div class="banner__details">
          <p class="banner__details--quote">
            Regular bookings<br />adjusted to your schedule
          </p>
          <p class="banner__details--specialQuote">
            Make up to £50/h with Dazlur
          </p>
        </div>
        <div class="banner__details--link">
          <a href="#">join the dazlur team</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="postcss" scoped>
.banner {
  img {
    w: 100%;
    h: auto;
    display: block;
  }

  img.on-mobile {
    display: none;
  }

  @media only map(breakpoints, phone) {
    img.on-mobile {
      display: block;
    }
    img.above-mobile {
      display: none;
    }

    .banner__content {
      position: relative;

      &:before {
        bg: url('~/assets/img/mobile-top.svg') no-repeat;
        content: '';
        w: 100%;
        position: absolute;
        height: 60px;
        top: -59px;
        left: 0;
        background-size: 100% 100%;
      }

      &--wr {
        .banner__logo {
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
            fz: 4.5rem;
            text-align: center;
            letter-spacing: 1rem;
          }
        }

        .banner__details {
          &--quote,
          &--specialQuote {
            color: map(colors, black);
          }

          &--link {
            display: none;
          }

          &--quote {
            fz: 2rem;
            fw: 600;
            text-align: center;
          }

          &--specialQuote {
            bg: none;
            p: 0;
            fz: 2rem;
            fw: normal;
          }
        }
      }
    }
  }

  &__content {
    position: absolute 0 * * 0;
    w: 100%;

    &--wr {
      w: 80%;
      m: 0 auto;
      overflow: hidden;
    }
  }

  &__logo {
    a {
      display: block;
      c: #fff;
      text-decoration: none;
      fw: 800;
      text-transform: capitalize;
      fz: 6rem;
      m: 1.8rem 0;
      letter-spacing: 1.6rem;
    }
  }

  &__details {
    &--quote,
    &--specialQuote {
      c: #fff;
      fw: 800;
    }

    &--quote {
      fz: 6rem;
    }

    &--specialQuote {
      bg: rgba(0, 0, 0, 0.4);
      p: 1.2rem 2.8rem;
      fz: 3.5rem;
      display: inline-block;
      mt: 0;
      border-radius: 3.5rem;
    }

    &--link {
      a {
        display: inline-block;
        bg: #fff;
        border-radius: 3.5rem;
        p: 1.2rem 2.8rem;
        text-transform: capitalize;
        fz: 1.5rem;
        text-decoration: none;
        c: map(colors, black);
        fw: 800;
      }
    }
  }
}
</style>
