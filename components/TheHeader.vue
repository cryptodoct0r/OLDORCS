<i18n>
{
  "uk": {
    "links": {
      "home": "Головна",
      "services": "Послуги",
      "portfolio": "Портфоліо",
      "contact": "Контакти"
    }
  },
  "ru": {
    "links": {
      "home": "Главная",
      "services": "услуги",
      "portfolio": "Портфолио",
      "contact": "Контакты"
    }
  }
}
</i18n>

<template>
  <header id="myHeader" class="menu_fixed">
    <b-navbar type="white" variant="white" class="container">
      <b-navbar-brand
        v-scroll-to="{
          el: '#hero',
          offset: -200,
        }"
        class="logo"
        :to="localePath({ name: 'index' }, $i18n.locale) + '#hero'"
      >
        <svg
          width="520"
          height="158"
          viewBox="0 0 520 158"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M227.476 107.267C227.476 120.103 221.133 126.538 208.456 126.569C195.803 126.569 189.48 120.131 189.48 107.267V51.185C189.48 38.349 195.803 31.928 208.456 31.928C221.133 31.928 227.476 38.348 227.476 51.185V107.267ZM214.249 51.185C214.249 47.069 212.334 44.997 208.501 44.969H208.405C204.604 44.969 202.708 47.038 202.708 51.185V107.267C202.708 111.41 204.622 113.483 208.455 113.483C212.316 113.483 214.248 111.409 214.248 107.267V51.185H214.249Z"
            fill="#DD6D48"
          />
          <path
            d="M238.879 125.073V33.379H252.106V112.032H273.181V125.073H238.879Z"
            fill="#DD6D48"
          />
          <path
            d="M284.585 33.379L304.961 33.424C316.71 33.424 322.58 39.84 322.58 52.68V105.816C322.58 118.62 316.71 125.026 304.961 125.026C304.773 125.026 304.492 125.035 304.119 125.072H284.585V33.379V33.379ZM297.813 46.42V112.032H303.606C307.439 112.032 309.358 109.959 309.358 105.817V52.681C309.358 48.507 307.439 46.42 303.606 46.42H297.813Z"
            fill="#DD6D48"
          />
          <path
            d="M371.882 107.267C371.882 120.103 365.54 126.538 352.863 126.569C340.214 126.569 333.888 120.131 333.888 107.267V51.185C333.888 38.349 340.213 31.928 352.863 31.928C365.54 31.928 371.882 38.348 371.882 51.185V107.267ZM358.655 51.185C358.655 47.069 356.741 44.997 352.908 44.969H352.817C349.01 44.969 347.115 47.038 347.115 51.185V107.267C347.115 111.41 349.029 113.483 352.863 113.483C356.727 113.483 358.655 111.409 358.655 107.267V51.185V51.185Z"
            fill="#5998BB"
          />
          <path
            d="M383.287 33.379L402.542 33.424C414.287 33.424 420.162 39.84 420.162 52.68V66.466C420.162 74.533 416.688 79.848 409.741 82.403L424.6 125.072H410.113L398.196 84.74L396.513 84.972V125.072H383.286V33.379H383.287ZM396.514 46.42V72.683H399.551C401.393 72.683 402.652 72.559 403.339 72.306C405.735 71.342 406.935 69.395 406.935 66.467V52.681C406.935 48.507 405.022 46.42 401.188 46.42H396.514V46.42Z"
            fill="#5998BB"
          />
          <path
            d="M469.647 107.267C469.647 120.103 463.307 126.538 450.626 126.569C437.977 126.569 431.651 120.131 431.651 107.267V51.185C431.651 38.349 437.976 31.928 450.626 31.928C463.307 31.928 469.647 38.348 469.647 51.185V63.521H456.42V51.185C456.42 47.069 454.505 44.997 450.672 44.969H450.582C446.78 44.969 444.879 47.038 444.879 51.185V107.267C444.879 111.41 446.793 113.483 450.627 113.483C454.487 113.483 456.42 111.409 456.42 107.267V94.932H469.648V107.267H469.647Z"
            fill="#5998BB"
          />
          <path
            d="M481.056 51.185C481.056 38.349 487.38 31.928 500.031 31.928C512.707 31.928 519.05 38.348 519.05 51.185V63.521H505.823V51.185C505.823 47.069 503.909 44.997 500.076 44.969H499.98C496.179 44.969 494.278 47.038 494.278 51.185V59.501C494.278 63.584 498.407 68.586 506.664 74.506C514.921 80.39 519.05 87.451 519.05 95.672V107.267C519.05 120.131 512.725 126.569 500.076 126.569C487.394 126.537 481.056 120.103 481.056 107.267V94.932H494.278V107.267C494.278 111.41 496.212 113.483 500.076 113.483C503.909 113.483 505.823 111.409 505.823 107.267V96.8C505.823 92.376 501.694 87.202 493.442 81.281C485.18 75.393 481.056 68.227 481.056 59.783V51.185Z"
            fill="#5998BB"
          />
          <path
            d="M158.022 79.117C158.022 122.55 122.799 157.762 79.348 157.762C35.897 157.762 0.671997 122.55 0.671997 79.117C0.671997 35.68 35.897 0.463989 79.348 0.463989C122.799 0.463989 158.022 35.68 158.022 79.117Z"
            fill="#5998BB"
          />
          <path
            d="M102.35 73.283C111.037 73.283 118.079 66.2436 118.079 57.56C118.079 48.8765 111.037 41.837 102.35 41.837C93.6631 41.837 86.621 48.8765 86.621 57.56C86.621 66.2436 93.6631 73.283 102.35 73.283Z"
            fill="#DD6D48"
          />
          <path
            d="M158.022 118.416H136.058L132.123 102.693L126.223 79.117L120.321 102.693L116.388 118.416H113.969L112.657 114.488L108.726 102.697L104.793 114.488L103.481 118.416H55.211L53.901 114.492L49.968 102.706L46.037 114.492L44.728 118.416H42.304L38.371 102.702L32.474 79.121L26.572 102.702L22.639 118.416H0.671997V126.273H20.672L20.669 126.278H32.474H42.104L42.102 126.282H49.968H57.837L57.832 126.273H100.86L100.858 126.278H108.726H116.592V126.273H158.022V118.416Z"
            fill="white"
          />
          <path
            d="M189.885 141.11H200.571V143.206H192.394V146.58H196.453C198.101 146.58 199.351 146.925 200.209 147.612C201.067 148.294 201.495 149.286 201.495 150.581C201.495 151.945 201.026 152.991 200.081 153.728C199.145 154.469 197.801 154.837 196.06 154.837H189.886V141.11H189.885ZM195.926 152.873C196.904 152.873 197.652 152.682 198.158 152.31C198.67 151.928 198.924 151.382 198.924 150.664C198.924 149.249 197.924 148.54 195.925 148.54H192.394V152.873H195.926Z"
            fill="black"
          />
          <path
            d="M213.253 141.701C214.135 142.092 214.812 142.656 215.276 143.383C215.753 144.115 215.985 144.984 215.985 145.993C215.985 146.984 215.753 147.853 215.276 148.589C214.812 149.33 214.134 149.894 213.253 150.29C212.371 150.681 211.335 150.876 210.143 150.876H207.046V154.837H204.496V141.11H210.143C211.334 141.11 212.371 141.305 213.253 141.701ZM212.562 148.012C213.131 147.539 213.426 146.871 213.426 145.993C213.426 145.115 213.131 144.442 212.562 143.969C211.98 143.501 211.139 143.264 210.029 143.264H207.046V148.716H210.029C211.139 148.717 211.979 148.485 212.562 148.012Z"
            fill="black"
          />
          <path
            d="M229.049 152.7V154.837H218.755V141.11H228.776V143.247H221.306V146.812H227.935V148.917H221.306V152.7H229.049V152.7Z"
            fill="black"
          />
          <path
            d="M244.268 141.11V154.837H241.722V148.953H234.623V154.837H232.073V141.11H234.623V146.775H241.722V141.11H244.268Z"
            fill="black"
          />
          <path
            d="M262.087 152.677V157.761H259.733V154.837H249.202V157.761H246.824L246.847 152.677H247.437C248.292 152.641 248.906 152.004 249.251 150.767C249.592 149.535 249.81 147.762 249.888 145.461L250.047 141.11H260.1V152.677H262.087ZM251.693 150.14C251.47 151.322 251.115 152.168 250.633 152.677H257.594V143.265H252.219L252.119 145.698C252.057 147.476 251.911 148.958 251.693 150.14Z"
            fill="black"
          />
          <path
            d="M264.811 141.11H267.317V150.859L274.697 141.11H277.066V154.837H274.56V145.111L267.18 154.837H264.811V141.11Z"
            fill="black"
          />
          <path
            d="M293.275 141.11V154.837H290.724V148.953H283.625V154.837H281.074V141.11H283.625V146.775H290.724V141.11H293.275Z"
            fill="black"
          />
          <path
            d="M306.579 143.265H299.767L299.79 154.837H297.279V141.11H306.592L306.579 143.265Z"
            fill="black"
          />
          <path
            d="M352.349 152.677V157.761H349.995V154.837H339.46V157.761H337.09L337.109 152.677H337.7C338.564 152.641 339.169 152.004 339.514 150.767C339.859 149.535 340.069 147.762 340.151 145.461L340.31 141.11H350.364V152.677H352.349ZM341.954 150.14C341.726 151.322 341.377 152.168 340.891 152.677H347.857V143.265H342.482L342.382 145.698C342.318 147.476 342.178 148.958 341.954 150.14Z"
            fill="black"
          />
          <path
            d="M355.073 141.11H357.583V150.859L364.953 141.11H367.326V154.837H364.821V145.111L357.446 154.837H355.073V141.11Z"
            fill="black"
          />
          <path
            d="M380.549 148.944C381.009 149.526 381.241 150.208 381.241 150.994C381.241 151.817 380.976 152.532 380.435 153.14C379.904 153.744 379.184 154.214 378.292 154.545C377.392 154.868 376.415 155.032 375.355 155.032C374.436 155.032 373.522 154.905 372.6 154.645C371.681 154.395 370.827 154.013 370.038 153.504L370.861 151.64C371.463 152.045 372.131 152.354 372.868 152.572C373.599 152.79 374.323 152.895 375.045 152.895C376.077 152.895 376.933 152.695 377.623 152.286C378.31 151.882 378.651 151.327 378.651 150.622C378.651 150.021 378.4 149.562 377.904 149.248C377.41 148.93 376.723 148.78 375.849 148.78H372.649V146.775H375.649C376.41 146.775 377.001 146.621 377.437 146.302C377.865 145.993 378.086 145.565 378.086 145.029C378.086 144.388 377.791 143.892 377.209 143.538C376.627 143.188 375.881 143.01 374.98 143.01C374.367 143.01 373.735 143.097 373.08 143.274C372.425 143.451 371.811 143.711 371.238 144.047L370.434 141.991C371.137 141.614 371.883 141.328 372.675 141.137C373.471 140.951 374.252 140.855 375.043 140.855C376.063 140.855 376.999 141.014 377.853 141.324C378.713 141.642 379.4 142.087 379.91 142.669C380.419 143.252 380.669 143.929 380.669 144.72C380.669 145.398 380.482 145.993 380.123 146.502C379.755 147.012 379.25 147.407 378.614 147.68C379.44 147.944 380.081 148.363 380.549 148.944Z"
            fill="black"
          />
          <path
            d="M393.518 151.659H386.652L385.301 154.838H382.673L388.852 141.111H391.363L397.56 154.838H394.891L393.518 151.659ZM392.676 149.663L390.088 143.656L387.515 149.663H392.676Z"
            fill="black"
          />
          <path
            d="M400.068 141.11H402.583V150.859L409.959 141.11H412.327V154.837H409.818V145.111L402.442 154.837H400.068V141.11V141.11ZM403.511 139.468C402.92 138.977 402.611 138.272 402.598 137.345H404.389C404.399 137.831 404.558 138.2 404.857 138.464C405.163 138.723 405.594 138.855 406.172 138.855C406.735 138.855 407.171 138.723 407.494 138.464C407.817 138.2 407.985 137.832 407.994 137.345H409.764C409.75 138.259 409.437 138.963 408.826 139.454C408.226 139.945 407.335 140.191 406.172 140.191C404.994 140.191 404.111 139.951 403.511 139.468Z"
            fill="black"
          />
          <path
            d="M428.538 141.11V154.837H425.987V148.953H418.888V154.837H416.337V141.11H418.888V146.775H425.987V141.11H428.538Z"
            fill="black"
          />
          <path
            d="M475.994 152.677V157.761H473.643V154.837H463.112V157.761H460.734L460.754 152.677H461.348C462.207 152.641 462.809 152.004 463.158 150.767C463.505 149.535 463.719 147.762 463.796 145.461L463.95 141.11H474.017V152.677H475.994ZM465.601 150.14C465.377 151.322 465.028 152.168 464.541 152.677H471.502V143.265H466.132L466.032 145.698C465.964 147.476 465.822 148.958 465.601 150.14Z"
            fill="black"
          />
          <path
            d="M487.466 141.701C488.344 142.092 489.027 142.656 489.49 143.383C489.968 144.115 490.198 144.984 490.198 145.993C490.198 146.984 489.968 147.853 489.49 148.589C489.026 149.33 488.344 149.894 487.466 150.29C486.579 150.681 485.543 150.876 484.357 150.876H481.26V154.837H478.709V141.11H484.356C485.543 141.11 486.579 141.305 487.466 141.701ZM486.771 148.012C487.344 147.539 487.63 146.871 487.63 145.993C487.63 145.115 487.344 144.442 486.771 143.969C486.194 143.501 485.348 143.264 484.239 143.264H481.26V148.716H484.239C485.348 148.717 486.193 148.485 486.771 148.012Z"
            fill="black"
          />
          <path
            d="M504.763 141.11L498.797 152.191C498.275 153.168 497.656 153.905 496.929 154.396C496.202 154.887 495.414 155.132 494.565 155.132C493.882 155.132 493.213 154.986 492.545 154.7L493.177 152.7C493.709 152.868 494.151 152.954 494.505 152.954C495.328 152.954 496.005 152.527 496.542 151.682L496.76 151.346L491.29 141.111H494.019L498.075 149.173L502.254 141.111H504.763V141.11Z"
            fill="black"
          />
          <path
            d="M512.319 149.054H509.768V154.838H507.259V141.11H509.768V146.857H512.397L516.344 141.11H519.044L514.356 147.757L519.222 154.837H516.344L512.319 149.054Z"
            fill="black"
          />
          <path
            d="M326.649 147.767C326.649 150.805 324.189 153.274 321.142 153.274C318.101 153.274 315.64 150.805 315.64 147.767C315.64 144.721 318.101 142.261 321.142 142.261C324.189 142.26 326.649 144.72 326.649 147.767Z"
            fill="black"
          />
          <path
            d="M450.859 147.767C450.859 150.805 448.394 153.274 445.357 153.274C442.314 153.274 439.845 150.805 439.845 147.767C439.845 144.721 442.314 142.261 445.357 142.261C448.395 142.26 450.859 144.72 450.859 147.767Z"
            fill="black"
          />
        </svg>
      </b-navbar-brand>

      <b-sidebar id="sidebar-right" backdrop shadow right>
        <div class="px-3 py-2 text-center">
          <b-navbar-nav v-b-scrollspy="200" class="d-block">
            <b-nav-item
              v-scroll-to="{
                el: '#hero',
                offset: -200,
              }"
              class="sbNav"
              :to="localePath({ name: 'index' }, $i18n.locale) + '#hero'"
            >
              {{ $t('links.home') }}
            </b-nav-item>

            <b-nav-item
              v-scroll-to="{
                el: '#services',
                offset: -120,
              }"
              class="sbNav"
              to="#services"
            >
              {{ $t('links.services') }}
            </b-nav-item>

            <b-nav-item
              v-scroll-to="{
                el: '#works',
                offset: -120,
              }"
              class="sbNav"
              to="#works"
            >
              {{ $t('links.portfolio') }}
            </b-nav-item>

            <b-nav-item
              v-scroll-to="{
                el: '#contact',
                offset: -120,
              }"
              class="sbNav"
              to="#contact"
            >
              {{ $t('links.contact') }}
            </b-nav-item>
            <div class="d-inline-flex sbLang">
              <b-nav-item :to="switchLocalePath('uk')">Укр</b-nav-item>
              <b-nav-item :to="switchLocalePath('ru')">Рус </b-nav-item>
            </div>
          </b-navbar-nav>
        </div>
      </b-sidebar>

      <div class="my-nav nav" is-nav>
        <b-navbar-nav v-b-scrollspy="200" class="ml-auto d-none d-lg-flex">
          <b-nav-item
            v-scroll-to="{
              el: '#hero',
              offset: -200,
            }"
            :to="localePath({ name: 'index' }, $i18n.locale) + '#hero'"
          >
            {{ $t('links.home') }}
          </b-nav-item>

          <b-nav-item
            v-scroll-to="{
              el: '#services',
              offset: -120,
            }"
            to="#services"
          >
            {{ $t('links.services') }}
          </b-nav-item>

          <b-nav-item
            v-scroll-to="{
              el: '#works',
              offset: -120,
            }"
            to="#works"
          >
            {{ $t('links.portfolio') }}
          </b-nav-item>

          <b-nav-item
            v-scroll-to="{
              el: '#contact',
              offset: -120,
            }"
            to="#contact"
          >
            {{ $t('links.contact') }}
          </b-nav-item>
        </b-navbar-nav>
      </div>

      <svg
        v-b-toggle.sidebar-right
        class="toggle-icon ml-auto d-lg-none d-flex"
        name="toggle-icon"
        xmlns="http://www.w3.org/2000/svg"
        width="30"
        height="26"
        viewBox="0 0 30 26"
      >
        <path
          d="M29.318,0H.682A.718.718,0,0,0,0,.75v1.5A.718.718,0,0,0,.682,3H29.318A.718.718,0,0,0,30,2.25V.75A.718.718,0,0,0,29.318,0Z"
          transform="translate(0 12)"
          fill="#0084a1"
        />
        <path
          d="M14.318,0H.682A.718.718,0,0,0,0,.75v1.5A.718.718,0,0,0,.682,3H14.318A.718.718,0,0,0,15,2.25V.75A.718.718,0,0,0,14.318,0Z"
          transform="translate(0 23)"
          fill="#0084a1"
        />
        <path
          d="M14.318,0H.682A.718.718,0,0,0,0,.75v1.5A.718.718,0,0,0,.682,3H14.318A.718.718,0,0,0,15,2.25V.75A.718.718,0,0,0,14.318,0Z"
          transform="translate(15)"
          fill="#0084a1"
        />
      </svg>

      <div></div>
    </b-navbar>

    <div class="lang xLarge">
      <nuxt-link :to="switchLocalePath('uk')">
        Укр
      </nuxt-link>
      <nuxt-link :to="switchLocalePath('ru')">
        Рус
      </nuxt-link>
    </div>
    <div class="lang large">
      <b-nav-item-dropdown style="padding: 12px 0;" text="Lang" right>
        <b-dropdown-item :to="switchLocalePath('uk')">Укр</b-dropdown-item>
        <b-dropdown-item :to="switchLocalePath('ru')">Рус</b-dropdown-item>
      </b-nav-item-dropdown>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
header {
  width: 100vw;
  height: 100px;

  background-color: #ffffff;

  display: flex;
  position: relative;

  z-index: 4;

  &.menu_fixed {
    position: fixed;
    width: 100vw;
    background-color: #fff;
    box-shadow: 0 10px 15px rgba(0, 0, 0, 0.05);
    top: 0;
  }

  .logo svg {
    width: auto;
    height: 65px;
    margin: auto 0;

    @media screen and (max-width: 600px) {
      height: 50px;
    }
  }

  .nav {
    display: flex;
    margin-left: auto;

    a.nav-link {
      list-style: none;
      font-style: normal;
      font-weight: 600;
      font-size: 16px;
      line-height: 20px;

      text-decoration: none;
      text-transform: capitalize;
      text-align: center;

      color: #666666;
      border-bottom: 0px #0084a1 solid;
      text-decoration: none;

      padding: 45px 0 30px 0;
      margin: 0 0 0 50px;

      transition: border-bottom 300ms linear, font-weight 300ms linear,
        color 300ms linear;
      -webkit-transition: border-bottom 300ms linear, font-weight 300ms linear,
        color 300ms linear;
      -moz-transition: border-bottom 300ms linear, font-weight 300ms linear,
        color 300ms linear;
      -ms-transition: border-bottom 300ms linear, font-weight 300ms linear,
        color 300ms linear;
      -o-transition: border-bottom 300ms linear, font-weight 300ms linear,
        color 300ms linear;

      &:hover,
      &.active {
        content: '';
        display: block;

        color: #0084a1;
        border-bottom: 5px #0084a1 solid;
      }
    }
  }

  .lang {
    display: flex;

    position: absolute;

    &.large {
      display: none;
      @media screen and (min-width: 1580px) and (max-width: 1729.9px) {
        display: flex;
        right: 20px;
      }
    }

    &.xLarge {
      display: none;
      @media screen and (min-width: 1730px) {
        display: flex;
        right: 4%;
      }
    }
    a {
      list-style: none;
      font-style: normal;
      font-weight: 500;
      font-size: 16px;
      line-height: 20px;
      text-decoration: none;
      text-transform: capitalize;

      color: #666666;

      padding: 45px 0;
      margin: 0 0 0 20px;

      transition: all 300ms ease;
      -webkit-transition: all 300ms ease;
      -moz-transition: all 300ms ease;
      -ms-transition: all 300ms ease;
      -o-transition: all 300ms ease;
    }

    a:hover,
    a.nuxt-link-exact-active {
      color: #0084a1;
    }

    a.nuxt-link-exact-active {
      font-weight: 600;
    }
  }
}

.animated {
  -webkit-animation-duration: 1s !important;
  animation-duration: 1s !important;
  -webkit-animation-fill-mode: both !important;
  animation-fill-mode: both !important;
}

.fadeInDown {
  -webkit-animation-name: fadeInDown;
  animation-name: fadeInDown;
}

@keyframes #{fadeInDown} {
  0% {
    -webkit-transform: translate3d(0, -40px, 0);
    transform: translate3d(0, -40px, 0);
  }
  100% {
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    opacity: 1;
  }
}

.toggle-icon {
  height: 26px;
  width: 30px;
  margin: auto 0;

  cursor: pointer;
}

#sidebar-right {
  .sbNav a.nav-link {
    list-style: none;
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 20px;

    text-decoration: none;
    text-transform: capitalize;
    text-align: center;

    color: #666666;
    border-bottom: 0px #0084a1 solid;
    text-decoration: none;

    margin: 30px;

    transition: border-bottom 300ms linear, font-weight 300ms linear,
      color 300ms linear;
    -webkit-transition: border-bottom 300ms linear, font-weight 300ms linear,
      color 300ms linear;
    -moz-transition: border-bottom 300ms linear, font-weight 300ms linear,
      color 300ms linear;
    -ms-transition: border-bottom 300ms linear, font-weight 300ms linear,
      color 300ms linear;
    -o-transition: border-bottom 300ms linear, font-weight 300ms linear,
      color 300ms linear;

    &:hover,
    &.active {
      content: '';
      display: block;

      color: #0084a1;
      border-bottom: 5px #0084a1 solid;
    }
  }

  .sbLang {
    display: inline-flex;
    position: absolute;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);

    a {
      list-style: none;
      font-style: normal;
      font-weight: 600;
      font-size: 16px;
      line-height: 20px;
      text-decoration: none;
      text-transform: capitalize;

      color: #666666;

      transition: all 300ms ease;
      -webkit-transition: all 300ms ease;
      -moz-transition: all 300ms ease;
      -ms-transition: all 300ms ease;
      -o-transition: all 300ms ease;

      &:hover,
      &.nuxt-link-exact-active {
        color: #0084a1;
      }
    }
  }
}
</style>
