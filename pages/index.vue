<template>
  <section
    class="
      container container--full container--wr container--ovh container--rel
      landing
    "
  >
    <div
      class="
        container container--block container--wr container--ovh container--rel
      "
    >
      <div class="container--block--2x landing__what">
        <h3>What is Dazlure?</h3>
        <p class="landing__what--special">
          Dazlure is a beauty services platform, that connects beaticians and
          clients. Our focus is on high quality and convenient service.
        </p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate,
          nulla dignissimos. At nam, maiores perferendis quod et velit saepe
          facilis suscipit itaque sit ipsum aliquam sed ratione omnis fugiat
          corporis incidunt soluta eum hic quas cumque. A porro, molestias quod
          reiciendis eveniet rerum facere eos placeat, quis earum adipisci modi
          et voluptatem doloremque tempora sint enim sunt distinctio sed alias!
        </p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero,
          pariatur quidem adipisci? Excepturi quia, alias, nemo, est molestiae
          error aperiam tenetur saepe pariatur quod culpa reprehenderit porro
          fuga! Vel id maiores doloremque eaque incidunt. Vel facere ad,
          recusandae voluptate autem?
        </p>
      </div>
      <div class="container--block--2x landing__what">
        <picture alt="Banner image">
          <source
            :srcSet="require('~/assets/img/what.png?webp')"
            type="image/webp"
          />
          <source
            :srcSet="require('~/assets/img/what.png')"
            type="image/jpeg"
          />
          <img :src="require('~/assets/img/what.png')" />
        </picture>
      </div>
    </div>
    <div
      class="
        container container--block container--wr container--ovh container--rel
        landing__segment
      "
    >
      <div class="container--block--4x">
        <div class="landing__segment--wr">
          <img src="~/assets/img/icin-1.png" alt="" />
          <h3>Easy Payments</h3>
          <p>
            We deposit your earnings directly into your bank account once a week
          </p>
        </div>
      </div>
      <div class="container--block--4x">
        <div class="landing__segment--wr">
          <img src="~/assets/img/icin-2.png" alt="" />
          <h3>Easy Payments</h3>
          <p>
            We deposit your earnings directly into your bank account once a week
          </p>
        </div>
      </div>
      <div class="container--block--4x">
        <div class="landing__segment--wr">
          <img src="~/assets/img/icin-3.png" alt="" />
          <h3>Flexible Schedule</h3>
          <p>
            While we do request that you complete up to two bookings per day,
            the rest of the time it is up to you how many bookings to pick up
          </p>
        </div>
      </div>
      <div class="container--block--4x">
        <div class="landing__segment--wr">
          <img src="~/assets/img/icin-4.png" alt="" />
          <h3>Safety</h3>
          <p>
            We ensure that we only work with reliable clients, and your safety
            at work is our priority
          </p>
        </div>
      </div>
    </div>
    <div
      class="
        container container--full container--wr container--rel
        landing__requirements
      "
    >
      <picture alt="Banner image">
        <source
          :srcSet="require('~/assets/img/requirement-min.png?webp')"
          type="image/webp"
        />
        <source
          :srcSet="require('~/assets/img/requirement-min.png')"
          type="image/jpeg"
        />
        <img :src="require('~/assets/img/requirement-min.png')" />
      </picture>
      <div class="landing__requirements--ctWr">
        <div
          class="
            container
            container--block
            container--wr
            container--ovh
            container--rel
          "
        >
          <div class="container--block--2x">
            <h3>Requirements</h3>
            <p class="landing__what--special">To work with eChíc you must:</p>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Cupiditate, nulla dignissimos. At nam, maiores perferendis quod et
              velit saepe facilis suscipit itaque sit ipsum aliquam sed ratione
              omnis fugiat corporis incidunt soluta eum hic quas cumque. A
              porro, molestias quod reiciendis eveniet rerum facere eos placeat,
              quis earum adipisci modi et voluptatem doloremque tempora sint
              enim sunt distinctio sed alias!
            </p>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
              sequi voluptates dolores obcaecati commodi laboriosam nulla
              nostrum ex, aut blanditiis.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
