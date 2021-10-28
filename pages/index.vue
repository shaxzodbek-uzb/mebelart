<template>
  <div>
    <!-- NAVBAR -->
    <header id="header">
      <div class="wrap">
        <a id="logo" href="javascript:void(0);">
          <span>LOGO</span>
        </a>
        <input id="bar" type="checkbox" />
        <label for="bar"></label>
        <nav id="navbar">
          <ul>
            <li>
              <a href="#" class="active">Home</a>
            </li>
            <li>
              <a href="#">About</a>
            </li>
            <li>
              <a href="#">Services</a>
            </li>
            <li>
              <a href="#">Team</a>
            </li>
            <li>
              <a href="#">Portfolio</a>
            </li>
            <li>
              <a href="#">Contact</a>
            </li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- SHOWCASE -->
    <section id="showcase">
      <div class="container">
        <h1 class="item" data-aos="fade-down">
          Эксклюзивные кухни
          <br />с топовой фурнитурой и
          <br />материалами от частного мастера
        </h1>
        <h3
          class="item"
          data-aos="fade-down"
          data-aos-delay="300"
        >Цена кухни = работа мастера + стоимость материалов</h3>
        <p
          class="item"
          data-aos="fade-down"
          data-aos-delay="600"
        >Работа по договору, без скрытых процентов и переплат</p>
        <a href="#" class="btn item" data-aos="zoom-out">Узнать стоимость кухни</a>
        <br />
        <a href="#products" class="scroll">
          <svg
            class="t-cover__arrow-svg"
            x="0px"
            y="0px"
            width="38.417px"
            height="18.592px"
            viewBox="0 0 38.417 18.592"
            style="enable-background:new 0 0 38.417 18.592;"
          >
            <g>
              <path
                fill="currentColor"
                d="M19.208,18.592c-0.241,0-0.483-0.087-0.673-0.261L0.327,1.74c-0.408-0.372-0.438-1.004-0.066-1.413c0.372-0.409,1.004-0.439,1.413-0.066L19.208,16.24L36.743,0.261c0.411-0.372,1.042-0.342,1.413,0.066c0.372,0.408,0.343,1.041-0.065,1.413L19.881,18.332C19.691,18.505,19.449,18.592,19.208,18.592z"
              />
            </g>
          </svg>
        </a>
      </div>
      <video autoplay muted loop>
        <source src="/video/rain.mp4" type="video/mp4" />Your browser does not support HTML5 video.
      </video>
    </section>

    <!-- PRODUCTS -->
    <section id="products">
      <div class="container">
        <!-- PRODUCT 1 -->
        <div class="product">
          <Gallery :images="['/image/1.jpeg','/image/2.jpeg','/image/3.jpeg','/image/4.jpeg']" />

          <aside>
            <h1>Кухня с антресолями + остров</h1>
            <p>
              Самая интересная деталь – это высота нижних баз – 100 см.
              <br />
              <br />Фасады – FENIX с лазерной кромкой.
              <br />Корпус – Egger Диамат Серый U963.
              <br />Система выдвижения – Blum LEGRABOX
              <br />Шкаф для запасов на системе Blum Space Tower
              <br />Петли - Blum clip top Blumotion и TipOn.
              <br />Подъемники - Blum Aventos HK Top.
              <br />Профиль Shuco черного цвета
              <br />Посудосушитель – VIBO GALAXY
              <br />Размер – 240х360 см
              <br />Остров – 120х90 см
            </p>
            <a href="#" class="btn item" data-aos="fade-up">хочу такую же!</a>
          </aside>
        </div>

        <!-- PRODUCT 2 -->
        <div class="product">
          <Gallery :images="['/image/1.jpeg','/image/2.jpeg','/image/3.jpeg','/image/4.jpeg']" />

          <aside>
            <h1>Кухня с антресолями + остров</h1>
            <p>
              Самая интересная деталь – это высота нижних баз – 100 см.
              <br />
              <br />Фасады – FENIX с лазерной кромкой.
              <br />Корпус – Egger Диамат Серый U963.
              <br />Система выдвижения – Blum LEGRABOX
              <br />Шкаф для запасов на системе Blum Space Tower
              <br />Петли - Blum clip top Blumotion и TipOn.
              <br />Подъемники - Blum Aventos HK Top.
              <br />Профиль Shuco черного цвета
              <br />Посудосушитель – VIBO GALAXY
              <br />Размер – 240х360 см
              <br />Остров – 120х90 см
            </p>
            <a href="#" class="btn item" data-aos="fade-up">хочу такую же!</a>
          </aside>
        </div>

        <!-- PRODUCT 3 -->
        <div class="product">
          <Gallery :images="['/image/1.jpeg','/image/2.jpeg','/image/3.jpeg','/image/4.jpeg']" />

          <aside>
            <h1>Кухня с антресолями + остров</h1>
            <p>
              Самая интересная деталь – это высота нижних баз – 100 см.
              <br />
              <br />Фасады – FENIX с лазерной кромкой.
              <br />Корпус – Egger Диамат Серый U963.
              <br />Система выдвижения – Blum LEGRABOX
              <br />Шкаф для запасов на системе Blum Space Tower
              <br />Петли - Blum clip top Blumotion и TipOn.
              <br />Подъемники - Blum Aventos HK Top.
              <br />Профиль Shuco черного цвета
              <br />Посудосушитель – VIBO GALAXY
              <br />Размер – 240х360 см
              <br />Остров – 120х90 см
            </p>
            <a href="#" class="btn item" data-aos="fade-up">хочу такую же!</a>
          </aside>
        </div>
      </div>
    </section>

    <!-- STAGE -->
    <section id="stage">
      <div class="container">
        <h2>Lorem ipsum dolor sit amet asdectetur.</h2>
        <div class="body">
          <div class="wrap">
            <div class="item" data-aos="fade-left">
              <b>01</b>
              <h4>Lorem, ipsum dolor.</h4>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Velit impedit ipsum aspernatur id.</p>
            </div>
            <div class="item" data-aos="fade-left" data-aos-delay="150">
              <b>02</b>
              <h4>Lorem, ipsum dolor.</h4>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Velit impedit ipsum aspernatur id.</p>
            </div>
          </div>
          <div class="wrap">
            <div class="item" data-aos="fade-left" data-aos-delay="300">
              <b>03</b>
              <h4>Lorem, ipsum dolor.</h4>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Velit impedit ipsum aspernatur id.</p>
            </div>
            <div class="item" data-aos="fade-left" data-aos-delay="450">
              <b>04</b>
              <h4>Lorem, ipsum dolor.</h4>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Velit impedit ipsum aspernatur id.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SERVICE -->
    <section id="service">
      <div class="container">
        <h2
          class="title item"
          data-aos="fade-down"
        >Ищете качественную современную кухню, но не понимаете за что стоит платить?</h2>
        <div class="body">
          <div class="wrap">
            <div class="text">
              <div>
                <h3>Lorem, ipsum dolor.</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus ducimus dicta explicabo eligendi ad iste natus in alias esse beatae deleniti, quia, fugiat voluptatibus! Molestiae in aliquid recusandae quas beatae.</p>
              </div>
            </div>
            <div class="img" style="background-image: url('/image/1.jpeg');"></div>
          </div>
          <div class="wrap">
            <div class="text">
              <div>
                <h3>Lorem, ipsum dolor.</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus ducimus dicta explicabo eligendi ad iste natus in alias esse beatae deleniti, quia, fugiat voluptatibus! Molestiae in aliquid recusandae quas beatae.</p>
              </div>
            </div>
            <div class="img" style="background-image: url('/image/1.jpeg');"></div>
          </div>
        </div>
        <div class="body">
          <div class="wrap">
            <div class="text">
              <div>
                <h3>Lorem, ipsum dolor.</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus ducimus dicta explicabo eligendi ad iste natus in alias esse beatae deleniti, quia, fugiat voluptatibus! Molestiae in aliquid recusandae quas beatae.</p>
              </div>
            </div>
            <div class="img" style="background-image: url('/image/1.jpeg');"></div>
          </div>
          <div class="wrap">
            <div class="text">
              <div>
                <h3>Lorem, ipsum dolor.</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus ducimus dicta explicabo eligendi ad iste natus in alias esse beatae deleniti, quia, fugiat voluptatibus! Molestiae in aliquid recusandae quas beatae.</p>
              </div>
            </div>
            <div class="img" style="background-image: url('/image/1.jpeg');"></div>
          </div>
        </div>
        <div class="body">
          <div class="wrap">
            <div class="text">
              <div>
                <h3>Lorem, ipsum dolor.</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus ducimus dicta explicabo eligendi ad iste natus in alias esse beatae deleniti, quia, fugiat voluptatibus! Molestiae in aliquid recusandae quas beatae.</p>
              </div>
            </div>
            <div class="img" style="background-image: url('/image/1.jpeg');"></div>
          </div>
          <div class="wrap">
            <div class="text">
              <div>
                <h3>Lorem, ipsum dolor.</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus ducimus dicta explicabo eligendi ad iste natus in alias esse beatae deleniti, quia, fugiat voluptatibus! Molestiae in aliquid recusandae quas beatae.</p>
              </div>
            </div>
            <div class="img" style="background-image: url('/image/1.jpeg');"></div>
          </div>
        </div>
        <div class="bottom">
          <div class="img">
            <img src="/image/4.jpeg" class="item" data-aos="fade-down" alt="img" />
          </div>
          <div class="content">
            <div class="wrap item" data-aos="fade-left">
              <div class="icon">
                <img src="/image/visit_card.svg" alt="icon" />
              </div>
              <div class="text">
                <h3>Lorem</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab a, similique ut accusamus optio, fugiat aperiam ratione soluta velit architecto placeat voluptatibus hic illum suscipit quasi quia! Expedita, odio debitis.</p>
              </div>
            </div>
            <div class="wrap item" data-aos="fade-left">
              <div class="icon">
                <img src="/image/pencil.svg" alt="icon" />
              </div>
              <div class="text">
                <h3>Lorem</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab a, similique ut accusamus optio, fugiat aperiam ratione soluta velit architecto placeat voluptatibus hic illum suscipit quasi quia! Expedita, odio debitis.</p>
              </div>
            </div>
            <div class="wrap item" data-aos="fade-left">
              <div class="icon">
                <img src="/image/hand_star.svg" alt="icon" />
              </div>
              <div class="text">
                <h3>Lorem</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab a, similique ut accusamus optio, fugiat aperiam ratione soluta velit architecto placeat voluptatibus hic illum suscipit quasi quia! Expedita, odio debitis.</p>
              </div>
            </div>
            <div class="wrap item" data-aos="fade-left">
              <div class="icon">
                <img src="/image/box.svg" alt="icon" />
              </div>
              <div class="text">
                <h3>Lorem</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab a, similique ut accusamus optio, fugiat aperiam ratione soluta velit architecto placeat voluptatibus hic illum suscipit quasi quia! Expedita, odio debitis.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="link">
          <a href="#" class="btn item" data-aos="zoom-out">Lorem, ipsum dolor.</a>
        </div>
      </div>
    </section>

    <!-- SOCIAL -->
    <section id="social">
      <div class="container">
        <div class="brands item" data-aos="zoom-in">
          <a href="#">
            <svg
              id="Layer_1"
              class="t-sociallinks__svg"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              x="0px"
              y="0px"
              width="64px"
              height="64px"
              viewBox="0 0 48 48"
              enable-background="new 0 0 48 48"
              xml:space="preserve"
            >
              <desc>Facebook</desc>
              <path
                fill="currentColor"
                d="M47.761,24c0,13.121-10.638,23.76-23.758,23.76C10.877,47.76,0.239,37.121,0.239,24c0-13.124,10.638-23.76,23.764-23.76C37.123,0.24,47.761,10.876,47.761,24 M20.033,38.85H26.2V24.01h4.163l0.539-5.242H26.2v-3.083c0-1.156,0.769-1.427,1.308-1.427h3.318V9.168L26.258,9.15c-5.072,0-6.225,3.796-6.225,6.224v3.394H17.1v5.242h2.933V38.85z"
              />
            </svg>
          </a>
          <a href="#">
            <svg
              id="Layer_1"
              class="t-sociallinks__svg"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              x="0px"
              y="0px"
              width="64px"
              height="64px"
              viewBox="0 0 48 48"
              enable-background="new 0 0 48 48"
              xml:space="preserve"
            >
              <desc>VK</desc>
              <path
                fill="currentColor"
                d="M47.761,24c0,13.121-10.639,23.76-23.76,23.76C10.878,47.76,0.239,37.121,0.239,24c0-13.123,10.639-23.76,23.762-23.76C37.122,0.24,47.761,10.877,47.761,24 M35.259,28.999c-2.621-2.433-2.271-2.041,0.89-6.25c1.923-2.562,2.696-4.126,2.45-4.796c-0.227-0.639-1.64-0.469-1.64-0.469l-4.71,0.029c0,0-0.351-0.048-0.609,0.106c-0.249,0.151-0.414,0.505-0.414,0.505s-0.742,1.982-1.734,3.669c-2.094,3.559-2.935,3.747-3.277,3.524c-0.796-0.516-0.597-2.068-0.597-3.171c0-3.449,0.522-4.887-1.02-5.259c-0.511-0.124-0.887-0.205-2.195-0.219c-1.678-0.016-3.101,0.007-3.904,0.398c-0.536,0.263-0.949,0.847-0.697,0.88c0.31,0.041,1.016,0.192,1.388,0.699c0.484,0.656,0.464,2.131,0.464,2.131s0.282,4.056-0.646,4.561c-0.632,0.347-1.503-0.36-3.37-3.588c-0.958-1.652-1.68-3.481-1.68-3.481s-0.14-0.344-0.392-0.527c-0.299-0.222-0.722-0.298-0.722-0.298l-4.469,0.018c0,0-0.674-0.003-0.919,0.289c-0.219,0.259-0.018,0.752-0.018,0.752s3.499,8.104,7.573,12.23c3.638,3.784,7.764,3.36,7.764,3.36h1.867c0,0,0.566,0.113,0.854-0.189c0.265-0.288,0.256-0.646,0.256-0.646s-0.034-2.512,1.129-2.883c1.15-0.36,2.624,2.429,4.188,3.497c1.182,0.812,2.079,0.633,2.079,0.633l4.181-0.056c0,0,2.186-0.136,1.149-1.858C38.281,32.451,37.763,31.321,35.259,28.999"
              />
            </svg>
          </a>
          <a href="#">
            <svg
              id="Layer_1"
              class="t-sociallinks__svg"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              x="0px"
              y="0px"
              width="64px"
              height="64px"
              viewBox="0 0 48 48"
              enable-background="new 0 0 48 48"
              xml:space="preserve"
            >
              <desc>Youtube</desc>
              <path
                fill="currentColor"
                d="M24 0.0130005C37.248 0.0130005 47.987 10.753 47.987 24C47.987 37.247 37.247 47.987 24 47.987C10.753 47.987 0.0130005 37.247 0.0130005 24C0.0130005 10.753 10.752 0.0130005 24 0.0130005ZM35.815 18.093C35.565 16.756 34.452 15.758 33.173 15.635C30.119 15.439 27.054 15.28 23.995 15.278C20.936 15.276 17.882 15.432 14.828 15.625C13.544 15.749 12.431 16.742 12.182 18.084C11.898 20.017 11.756 21.969 11.756 23.92C11.756 25.871 11.898 27.823 12.182 29.756C12.431 31.098 13.544 32.21 14.828 32.333C17.883 32.526 20.935 32.723 23.995 32.723C27.053 32.723 30.121 32.551 33.173 32.353C34.452 32.229 35.565 31.084 35.815 29.747C36.101 27.817 36.244 25.868 36.244 23.919C36.244 21.971 36.101 20.023 35.815 18.093ZM21.224 27.435V20.32L27.851 23.878L21.224 27.435Z"
              />
            </svg>
          </a>
          <a href="#">
            <svg
              id="Layer_1"
              class="t-sociallinks__svg"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              width="64px"
              height="64px"
              viewBox="0 0 30 30"
              xml:space="preserve"
            >
              <desc>Instagram</desc>
              <path
                fill="currentColor"
                d="M15,11.014 C12.801,11.014 11.015,12.797 11.015,15 C11.015,17.202 12.802,18.987 15,18.987 C17.199,18.987 18.987,17.202 18.987,15 C18.987,12.797 17.199,11.014 15,11.014 L15,11.014 Z M15,17.606 C13.556,17.606 12.393,16.439 12.393,15 C12.393,13.561 13.556,12.394 15,12.394 C16.429,12.394 17.607,13.561 17.607,15 C17.607,16.439 16.444,17.606 15,17.606 L15,17.606 Z"
              />
              <path
                fill="currentColor"
                d="M19.385,9.556 C18.872,9.556 18.465,9.964 18.465,10.477 C18.465,10.989 18.872,11.396 19.385,11.396 C19.898,11.396 20.306,10.989 20.306,10.477 C20.306,9.964 19.897,9.556 19.385,9.556 L19.385,9.556 Z"
              />
              <path
                fill="currentColor"
                d="M15.002,0.15 C6.798,0.15 0.149,6.797 0.149,15 C0.149,23.201 6.798,29.85 15.002,29.85 C23.201,29.85 29.852,23.202 29.852,15 C29.852,6.797 23.201,0.15 15.002,0.15 L15.002,0.15 Z M22.666,18.265 C22.666,20.688 20.687,22.666 18.25,22.666 L11.75,22.666 C9.312,22.666 7.333,20.687 7.333,18.28 L7.333,11.734 C7.333,9.312 9.311,7.334 11.75,7.334 L18.25,7.334 C20.688,7.334 22.666,9.312 22.666,11.734 L22.666,18.265 L22.666,18.265 Z"
              />
            </svg>
          </a>
        </div>
        <div class="youtube item" data-aos="zoom-out">
          <iframe
            src="https://www.youtube.com/embed/Ww-TlBa5pdE"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
      </div>
    </section>

    <!-- DESIGN -->
    <section id="design">
      <div class="container">
        <div class="desk">
          <div class="text">
            <div class="wrap">
              <h3 class="item" data-aos="fade-right">Lorem ipsum dolor sit amet.</h3>
              <p
                class="item"
                data-aos="fade-right"
                data-aos-delay="100"
              >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsa non cupiditate neque reprehenderit facilis sunt tempore est doloremque, quaerat temporibus. Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus porro possimus fugiat doloribus laboriosam eligendi natus dolore impedit vitae tempora voluptates, reprehenderit facere. Iure non minus eligendi explicabo obcaecati in.</p>
            </div>
          </div>
          <div class="img item" data-aos="fade-right">
            <img src="/image/laptop.webp" alt="laptop" />
          </div>
        </div>
        <div class="link">
          <a href="#" class="btn">Lorem, ipsum dolor.</a>
        </div>
        <div class="bottom">
          <!-- CENTER IMAGE -->
          <img src="/image/drawer.webp" class="drawer" alt="drawer" />

          <!-- ANIMATED CROSS -->
          <img src="/image/cross.png" class="cross-0" alt="cross" />

          <!-- POINTS -->
          <img src="/image/cross.png" class="cross-1" alt="cross" />
          <div class="drawer-1">
            <img src="/image/1.jpeg" alt="1" />
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos ea consequatur natus culpa a quaerat distinctio libero voluptas velit temporibus.</p>
          </div>
          <img src="/image/cross.png" class="cross-2" alt="cross" />
          <div class="drawer-2">
            <img src="/image/2.jpeg" alt="2" />
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos ea consequatur natus culpa a quaerat distinctio libero voluptas velit temporibus.</p>
          </div>
          <img src="/image/cross.png" class="cross-3" alt="cross" />
          <div class="drawer-3">
            <img src="/image/3.jpeg" alt="3" />
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos ea consequatur natus culpa a quaerat distinctio libero voluptas velit temporibus.</p>
          </div>
          <img src="/image/cross.png" class="cross-4" alt="cross" />
          <div class="drawer-4">
            <img src="/image/4.jpeg" alt="4" />
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos ea consequatur natus culpa a quaerat distinctio libero voluptas velit temporibus.</p>
          </div>
          <img src="/image/cross.png" class="cross-5" alt="cross" />
          <div class="drawer-5">
            <img src="/image/5.jpeg" alt="5" />
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos ea consequatur natus culpa a quaerat distinctio libero voluptas velit temporibus.</p>
          </div>
          <img src="/image/cross.png" class="cross-6" alt="cross" />
          <div class="drawer-6">
            <img src="/image/1.jpeg" alt="6" />
            <p>Lorem ipsum dolor sit amet cnatus culpa a quaerat distinctio libero voluptas velit temporibus.</p>
          </div>
          <img src="/image/cross.png" class="cross-7" alt="cross" />
          <div class="drawer-7">
            <img src="/image/2.jpeg" alt="7" />
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos ea consequatur natus culpa a quaerat distinctio libero voluptas velit temporibus.</p>
          </div>
          <img src="/image/cross.png" class="cross-8" alt="cross" />
          <div class="drawer-8">
            <img src="/image/3.jpeg" alt="8" />
            <p>Lorem ipsum dolor sit ameta quaerat distinctio libero voluptas velit temporibus.</p>
          </div>
          <img src="/image/cross.png" class="cross-9" alt="cross" />
          <div class="drawer-9">
            <img src="/image/5.jpeg" alt="9" />
            <p>Lorem ipsum dculpa a quaerat distas velit temporibus.</p>
          </div>
        </div>
      </div>
    </section>

    <Accardions />

    <!-- FEEDBACK -->
    <section id="feedback">
      <h2 class="title">Lorem</h2>

      <carousel items="1" loop="true" nav="true" smart-speed="700" animate-out="fadeOut">
        <div class="item">
          <div class="content">
            <img src="/image/2.jpeg" alt="img" />
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita distinctio ex labore excepturi rerum quae nemo, nulla laboriosam eum repellat ipsa praesentium vel cum molestiae facilis vero, repudiandae delectus velit.</p>
            <h4>Alex</h4>
            <small>Lorem, ipsum.</small>
          </div>
        </div>

        <div class="item">
          <div class="content">
            <img src="/image/4.jpeg" alt="img" />
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita distinctio ex labore excepturi rerum quae nemo, nulla laboriosam eum repellat ipsa praesentium vel cum molestiae facilis vero, repudiandae delectus velit. Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore sint, expedita pariatur fugiat minima tenetur? Vero a velit, amet, ex porro sit suscipit incidunt illum, dolore unde accusantium blanditiis vel.</p>
            <h4>Alex</h4>
            <small>Lorem, ipsum.</small>
          </div>
        </div>

        <div class="item">
          <div class="content">
            <img src="/image/5.jpeg" alt="img" />
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita distinctio ex labore excepturi rerum quae nemo, nulla laboriosam eum repellat ipsa praesentium vel cum molestiae facilis vero, repudiandae delectus velit.
              <br />
              <br />Lorem ipsum dolor, sit amet consectetur adipisicing elit. Autem asperiores, mollitia beatae alias deserunt neque ab quo animi sapiente? Sit illum repellat similique beatae modi fugit veritatis voluptatum rerum maiores!
              <br />
              <br />Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum porro optio reiciendis laudantium, ut quasi, quos deleniti earum ducimus molestias magni necessitatibus id qui tenetur facilis exercitationem cumque incidunt aliquam!
            </p>
            <h4>Alex</h4>
            <small>Lorem, ipsum.</small>
          </div>
        </div>
      </carousel>
    </section>

    <!-- SPONSORES -->
    <section id="sponsores">
      <div class="container">
        <h2 class="title">Lorem ipsum dolor sit amet consectetur adipisicing.</h2>
        <div class="brands">
          <div class="brand">
            <img src="/image/blum2.webp" alt="brand" />
          </div>
          <div class="brand">
            <img src="/image/blum2.webp" alt="brand" />
          </div>
          <div class="brand">
            <img src="/image/blum2.webp" alt="brand" />
          </div>
          <div class="brand">
            <img src="/image/blum2.webp" alt="brand" />
          </div>
          <div class="brand">
            <img src="/image/blum2.webp" alt="brand" />
          </div>
          <div class="brand">
            <img src="/image/rusta.webp" alt="brand" />
          </div>
          <div class="brand">
            <img src="/image/blum2.webp" alt="brand" />
          </div>
          <div class="brand">
            <img src="/image/blum2.webp" alt="brand" />
          </div>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <div class="container">
        <h2 class="title">Contacts</h2>
        <p>Alex Johnson</p>
        <span>
          Tel:
          <a href="tel:+9999999999">+9 (999) 999 99 99</a>
        </span>
        <span>
          E-mail:
          <a href="mailto:lorem@gmail.com">lorem@gmail.com</a>
        </span>
        <div class="socials">
          <a href="#">
            <svg
              id="Layer_1"
              class="t-sociallinks__svg"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              x="0px"
              y="0px"
              width="30px"
              height="30px"
              viewBox="0 0 48 48"
              enable-background="new 0 0 48 48"
              xml:space="preserve"
            >
              <desc>Youtube</desc>
              <path
                fill="currentColor"
                d="M24 0.0130005C37.248 0.0130005 47.987 10.753 47.987 24C47.987 37.247 37.247 47.987 24 47.987C10.753 47.987 0.0130005 37.247 0.0130005 24C0.0130005 10.753 10.752 0.0130005 24 0.0130005ZM35.815 18.093C35.565 16.756 34.452 15.758 33.173 15.635C30.119 15.439 27.054 15.28 23.995 15.278C20.936 15.276 17.882 15.432 14.828 15.625C13.544 15.749 12.431 16.742 12.182 18.084C11.898 20.017 11.756 21.969 11.756 23.92C11.756 25.871 11.898 27.823 12.182 29.756C12.431 31.098 13.544 32.21 14.828 32.333C17.883 32.526 20.935 32.723 23.995 32.723C27.053 32.723 30.121 32.551 33.173 32.353C34.452 32.229 35.565 31.084 35.815 29.747C36.101 27.817 36.244 25.868 36.244 23.919C36.244 21.971 36.101 20.023 35.815 18.093ZM21.224 27.435V20.32L27.851 23.878L21.224 27.435Z"
              />
            </svg>
          </a>
          <a href="#">
            <svg
              id="Layer_1"
              class="t-sociallinks__svg"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              width="30px"
              height="30px"
              viewBox="0 0 30 30"
              xml:space="preserve"
            >
              <desc>Instagram</desc>
              <path
                fill="currentColor"
                d="M15,11.014 C12.801,11.014 11.015,12.797 11.015,15 C11.015,17.202 12.802,18.987 15,18.987 C17.199,18.987 18.987,17.202 18.987,15 C18.987,12.797 17.199,11.014 15,11.014 L15,11.014 Z M15,17.606 C13.556,17.606 12.393,16.439 12.393,15 C12.393,13.561 13.556,12.394 15,12.394 C16.429,12.394 17.607,13.561 17.607,15 C17.607,16.439 16.444,17.606 15,17.606 L15,17.606 Z"
              />
              <path
                fill="currentColor"
                d="M19.385,9.556 C18.872,9.556 18.465,9.964 18.465,10.477 C18.465,10.989 18.872,11.396 19.385,11.396 C19.898,11.396 20.306,10.989 20.306,10.477 C20.306,9.964 19.897,9.556 19.385,9.556 L19.385,9.556 Z"
              />
              <path
                fill="currentColor"
                d="M15.002,0.15 C6.798,0.15 0.149,6.797 0.149,15 C0.149,23.201 6.798,29.85 15.002,29.85 C23.201,29.85 29.852,23.202 29.852,15 C29.852,6.797 23.201,0.15 15.002,0.15 L15.002,0.15 Z M22.666,18.265 C22.666,20.688 20.687,22.666 18.25,22.666 L11.75,22.666 C9.312,22.666 7.333,20.687 7.333,18.28 L7.333,11.734 C7.333,9.312 9.311,7.334 11.75,7.334 L18.25,7.334 C20.688,7.334 22.666,9.312 22.666,11.734 L22.666,18.265 L22.666,18.265 Z"
              />
            </svg>
          </a>
          <a href="#">
            <svg
              id="Layer_1"
              class="t-sociallinks__svg"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              x="0px"
              y="0px"
              width="30px"
              height="30px"
              viewBox="0 0 49 48"
              enable-background="new 0 0 49 48"
              xml:space="preserve"
            >
              <desc>Pinterest</desc>
              <path
                fill="currentColor"
                d="M49 24C49 37.254 38.254 48 25.001 48C11.744 48 0.997986 37.254 0.997986 24C0.997986 10.744 11.744 0 25.001 0C38.254 0 49 10.744 49 24ZM18.372 38.811C18.399 39.016 18.662 39.065 18.781 38.911C18.951 38.688 21.146 35.979 21.892 33.272C22.103 32.504 23.104 28.534 23.104 28.534C23.703 29.679 25.453 30.682 27.314 30.682C32.853 30.682 36.611 25.633 36.611 18.873C36.611 13.762 32.282 9 25.702 9C17.516 9 13.388 14.871 13.388 19.766C13.388 22.729 14.51 25.366 16.915 26.348C17.31 26.51 17.664 26.354 17.778 25.918C17.858 25.615 18.046 24.853 18.131 24.533C18.245 24.101 18.201 23.951 17.883 23.574C17.189 22.756 16.745 21.695 16.745 20.193C16.745 15.84 20.004 11.941 25.229 11.941C29.856 11.941 32.398 14.769 32.398 18.544C32.398 23.513 30.2 27.706 26.937 27.706C25.133 27.706 23.784 26.216 24.215 24.386C24.733 22.204 25.737 19.849 25.737 18.273C25.737 16.863 24.979 15.685 23.413 15.685C21.57 15.685 20.09 17.593 20.09 20.146C20.09 21.773 20.64 22.873 20.64 22.873C20.64 22.873 18.754 30.863 18.423 32.264C17.766 35.051 18.324 38.467 18.372 38.811Z"
              />
            </svg>
          </a>
        </div>
      </div>
    </section>

    <!-- FOOTER -->
    <footer>
      <div class="container">
        ВЕСЬ КОНТЕНТ ПРИНАДЛЕЖИТ
        <b>recart -m</b>
        <br />
        <a href="#">дизайнер сайта</a>
      </div>
    </footer>
  </div>
</template>

<script>
import carousel from 'v-owl-carousel'
import aosMixin from '~/mixins/aos'
export default {
  components: { carousel },
  mixins: [aosMixin],
  data() {
    return {
      options: {
        items: 1,
        loop: true,
        nav: true,
        smartSpeed: 700,
        animateOut: 'fadeOut'
      }
    }
  }
}
</script>
