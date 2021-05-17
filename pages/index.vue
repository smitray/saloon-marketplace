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
    <div
      class="
        container container--block container--wr container--ovh container--rel
      "
    >
      <h3 class="header--services">Featured Services</h3>
    </div>
    <div
      class="
        container container--block container--wr container--ovh container--rel
        landing__professional
      "
    >
      <div class="container--block--3x">
        <div class="landing__professional--wr">
          <picture alt="Banner image">
            <source
              :srcSet="require('~/assets/img/waxing.png?webp')"
              type="image/webp"
            />
            <source
              :srcSet="require('~/assets/img/waxing.png')"
              type="image/jpeg"
            />
            <img :src="require('~/assets/img/waxing.png')" />
          </picture>
          <h3>Body & Waxing</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        </div>
      </div>
      <div class="container--block--3x">
        <div class="landing__professional--wr">
          <picture alt="Banner image">
            <source
              :srcSet="require('~/assets/img/manicure.png?webp')"
              type="image/webp"
            />
            <source
              :srcSet="require('~/assets/img/manicure.png')"
              type="image/jpeg"
            />
            <img :src="require('~/assets/img/manicure.png')" />
          </picture>
          <h3>Manicure & Pedicure</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        </div>
      </div>
      <div class="container--block--3x">
        <div class="landing__professional--wr">
          <picture alt="Banner image">
            <source
              :srcSet="require('~/assets/img/massage.png?webp')"
              type="image/webp"
            />
            <source
              :srcSet="require('~/assets/img/massage.png')"
              type="image/jpeg"
            />
            <img :src="require('~/assets/img/massage.png')" />
          </picture>
          <h3>Massage</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        </div>
      </div>
    </div>

    <div
      class="
        container container--full container--wr container--rel container--ovh
        landing__join
      "
    >
      <h3>join now</h3>
      <div
        class="
          container container--block container--wr container--ovh container--rel
        "
      >
        <ul>
          <li :class="{ active: form_slider === 1 }">
            Enter your postcode
            <div class="landing__join--icons">
              <img src="~/assets/img/join-1.png" alt="" />
            </div>
          </li>
          <li :class="{ active: form_slider === 2 }">
            phone verification
            <div class="landing__join--icons">
              <img src="~/assets/img/join-2.png" alt="" />
            </div>
          </li>
          <li :class="{ active: form_slider === 3 }">
            contact details
            <div class="landing__join--icons">
              <img src="~/assets/img/join-3.png" alt="" />
            </div>
          </li>
          <li :class="{ active: form_slider === 4 }">
            upload the documents
            <div class="landing__join--icons">
              <img src="~/assets/img/join-4.png" alt="" />
            </div>
          </li>
        </ul>
        <form action="#" enctype="multipart/form-data">
          <div v-if="form_slider === 1" class="form__slider">
            <h4>Enter your postcode to get started</h4>
            <input type="text" placeholder="Enter your postcode" />
          </div>
          <div v-if="form_slider === 2" class="form__slider">
            <h4>Please verify your phone</h4>
            <input type="text" placeholder="Enter your phone" />
            <input
              type="text"
              placeholder="Please enter the OTP you received"
            />
          </div>
          <div v-if="form_slider === 3" class="form__slider">
            <h4>Please add your personal information</h4>
            <input type="text" placeholder="Your first name" />
            <input type="text" placeholder="Your last name" />
            <input type="text" placeholder="Your address" />
            <input type="text" placeholder="Passport number" />
            <input type="text" placeholder="Nil number" />
          </div>
          <div v-if="form_slider === 4" class="form__slider">
            <h4>Please provide the following documents</h4>
            <div class="form__slider--document">
              <p>Proof of Address (Format: jpg, jpeg, png, pdf)</p>
              <input ref="addressProof" type="file" />
              <p>Your CV (Format: doc or keynote)</p>
              <input ref="applicantCV" type="file" />
              <p>
                PROOF OF THE RIGHT TO WORK (Visa/Residence Card) (applicable for
                non-EU citizen) (Format: jpg, jpeg, png, pdf)
              </p>
              <input ref="rightToWork" type="file" />
              <label for="tnc"
                ><input id="tnc" type="checkbox" name="tnc" />I HAVE READ AND
                ACCEPT THE DAZLURE BEAUTICIANS' SERVICE AGREEMENT</label
              >
            </div>
            <input type="submit" value="Submit" class="btn-primary" />
          </div>
          <a
            v-if="form_slider !== 4"
            href="#"
            class="btn-primary"
            @click.prevent="nextForm"
            >Next</a
          >
        </form>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data() {
    return {
      form_slider: 1,
    }
  },
  methods: {
    nextForm() {
      this.form_slider += 1
    },
  },
})
</script>
