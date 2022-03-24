<template>
  <section class="menu-section sec-padding" id="our-menu">
    <div class="container">
      <div class="row">
        <div class="section-title">
          <h2 data-title="order now">наше меню</h2>
        </div>
      </div>
      <div class="row">
        <div class="menu-tabs">
          <button type="button" class="menu-tab-item active" data-target="#zav">
            завтрак
          </button>
          <button type="button" class="menu-tab-item" data-target="#yzh">
            ужин
          </button>
          <button type="button" class="menu-tab-item" data-target="#lunch">
            вега
          </button>
          <button type="button" class="menu-tab-item" data-target="#dinner">
            Супы
          </button>
          <button type="button" class="menu-tab-item" data-target="#drinks">
            напитки
          </button>
          <button type="button" class="menu-tab-item" data-target="#desserts">
            Десерты
          </button>
        </div>
        <div class="row menu-tab-content active" id="zav">
          <div class="menu-item">
            <div class="menu-item-title">
              <img src="../assets/img/menu/zav/1.jpg" alt="1" />
              <h3>Омлет с сыром и зеленью</h3>
            </div>
            <div class="menu-item-price">₽200.00</div>
          </div>
          <div class="menu-item">
            <div class="menu-item-title">
              <img src="../assets/img/menu/zav/2.jpg" alt="1" />
              <h3>Ленивые вареники</h3>
            </div>
            <div class="menu-item-price">₽187.00</div>
          </div>
          <div class="menu-item">
            <div class="menu-item-title">
              <img src="../assets/img/menu/zav/3.jpg" alt="1" />
              <h3>Сырники по-аджарски</h3>
            </div>
            <div class="menu-item-price">₽195.00</div>
          </div>
        </div>
        <div class="row menu-tab-content" id="yzh">
          <div class="menu-item">
            <div class="menu-item-title">
              <img src="../assets/img/menu/yzh/1.jpg" alt="1" />
              <h3>Овощной суп</h3>
            </div>
            <div class="menu-item-price">₽100.00</div>
          </div>
          <div class="menu-item">
            <div class="menu-item-title">
              <img src="../assets/img/menu/yzh/2.jpg" alt="1" />
              <h3>Гречка по-купечески</h3>
            </div>
            <div class="menu-item-price">₽190.00</div>
          </div>
          <div class="menu-item">
            <div class="menu-item-title">
              <img src="../assets/img/menu/yzh/3.jpg" alt="1" />
              <h3>Лагман с курицей</h3>
            </div>
            <div class="menu-item-price">₽200.00</div>
          </div>
        </div>
      </div>
      <div class="row menu-tab-content" id="lunch">
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/vegan/1_vegan.jpg" alt="1" />
            <h3>Рис с овощами</h3>
          </div>
          <div class="menu-item-price">₽50.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/vegan/2_vegan.jpg" alt="1" />
            <h3>Вегетарианский пулао</h3>
          </div>
          <div class="menu-item-price">₽60.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/vegan/3_vegan.jpg" alt="1" />
            <h3>Постные шарики с кунжутом</h3>
          </div>
          <div class="menu-item-price">₽30.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/vegan/4_vegan.jpg" alt="1" />
            <h3>Картофельные рулетики с грибами</h3>
          </div>
          <div class="menu-item-price">₽50.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/vegan/5_vegan.jpg" alt="1" />
            <h3>Капустные котлеты</h3>
          </div>
          <div class="menu-item-price">₽20.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/vegan/6_vegan.jpg" alt="1" />
            <h3>Томатный суп с фасолью и рисом</h3>
          </div>
          <div class="menu-item-price">₽30.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/vegan/7_vegan.jpg" alt="1" />
            <h3>Овощная лазанья из лаваша</h3>
          </div>
          <div class="menu-item-price">₽90.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/vegan/8_vegan.jpg" alt="1" />
            <h3>Морковный торт</h3>
          </div>
          <div class="menu-item-price">₽70.00</div>
        </div>
      </div>
      <div class="row menu-tab-content" id="dinner">
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/sup/sup_1.jpg" alt="1" />
            <h3>Суп "Харчо"</h3>
          </div>
          <div class="menu-item-price">₽40.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/sup/sup_2.jpg" alt="1" />
            <h3>Куриный суп с вермишелью</h3>
          </div>
          <div class="menu-item-price">₽50.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/sup/sup_3.jpg" alt="1" />
            <h3>Тосканский суп с фаршем</h3>
          </div>
          <div class="menu-item-price">₽60.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/sup/sup_4.jpg" alt="1" />
            <h3>Сырный суп</h3>
          </div>
          <div class="menu-item-price">₽60.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/sup/sup_5.jpg" alt="1" />
            <h3>Суп картофельный с клецками</h3>
          </div>
          <div class="menu-item-price">₽50.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/sup/sup_6.jpg" alt="1" />
            <h3>Суп "Затируха"</h3>
          </div>
          <div class="menu-item-price">₽60.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/sup/sup_7.jpg" alt="1" />
            <h3>Гречневый суп</h3>
          </div>
          <div class="menu-item-price">₽30.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/sup/sup_8.jpg" alt="1" />
            <h3>Гороховый суп</h3>
          </div>
          <div class="menu-item-price">₽30.00</div>
        </div>
      </div>
      <div class="row menu-tab-content" id="drinks">
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/drink/drink_1.jpg" alt="1" />
            <h3>Горячий шоколад</h3>
          </div>
          <div class="menu-item-price">₽20.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/drink/drink_2.jpg" alt="1" />
            <h3>Десерт из овсянки</h3>
          </div>
          <div class="menu-item-price">₽15.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/drink/drink_3.jpg" alt="1" />
            <h3>Зеленый смузи</h3>
          </div>
          <div class="menu-item-price">₽30.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/drink/drink_4.jpg" alt="1" />
            <h3>Кисель из черной смородины</h3>
          </div>
          <div class="menu-item-price">₽25.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/drink/drink_5.jpeg" alt="1" />
            <h3>Десерт с фруктовым пюре</h3>
          </div>
          <div class="menu-item-price">₽30.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/drink/drink_6.jpg" alt="1" />
            <h3>Лимонад</h3>
          </div>
          <div class="menu-item-price">₽10.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/drink/drink_7.jpg" alt="1" />
            <h3>Имбирный тоник</h3>
          </div>
          <div class="menu-item-price">₽40.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/drink/drink_8.jpg" alt="1" />
            <h3>Смузи со шпинатом</h3>
          </div>
          <div class="menu-item-price">₽20.00</div>
        </div>
      </div>
      <div class="row menu-tab-content" id="desserts">
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/desert/desert_1.jpg" alt="1" />
            <h3>Фунтовый кекс из цельнозерновой муки</h3>
          </div>
          <div class="menu-item-price">₽30.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/desert/desert_2.jpg" alt="1" />
            <h3>Пироженые с шоколадом</h3>
          </div>
          <div class="menu-item-price">₽45.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/desert/desert_3.jpg" alt="1" />
            <h3>Мраморный банановый хлеб</h3>
          </div>
          <div class="menu-item-price">₽35.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/desert/desert_4.jpg" alt="1" />
            <h3>Гранулы из замороженного йогурта</h3>
          </div>
          <div class="menu-item-price">₽20.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/desert/desert_5.jpg" alt="1" />
            <h3>Хрустящие крекеры</h3>
          </div>
          <div class="menu-item-price">₽10.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/desert/desert_6.jpg" alt="1" />
            <h3>Полезные пироженые Брауни</h3>
          </div>
          <div class="menu-item-price">₽50.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/desert/desert_7.jpg" alt="1" />
            <h3>Мини сэндвич с мороженым и печеньем</h3>
          </div>
          <div class="menu-item-price">₽45.00</div>
        </div>
        <div class="menu-item">
          <div class="menu-item-title">
            <img src="../assets/img/menu/desert/desert_8.jpg" alt="1" />
            <h3>Ангельский бисквит из яичных белков</h3>
          </div>
          <div class="menu-item-price">₽60.00</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Menu.vue",
  data() {
    return {};
  },
  methods: {
    menuTabs(e) {
      const menuTabs = document.querySelector(".menu-tabs");
      if (
        e.target.classList.contains("menu-tab-item") &&
        !e.target.classList.contains("active")
      ) {
        const target = e.target.getAttribute("data-target");
        menuTabs.querySelector(".active").classList.remove("active");
        e.target.classList.add("active");
        const menuSection = document.querySelector(".menu-section");
        menuSection
          .querySelector(".menu-tab-content.active")
          .classList.remove("active");
        menuSection.querySelector(target).classList.add("active");
      }
    },
  },
  mounted() {
    window.addEventListener("click", this.menuTabs);
  },
  beforeDestroy() {
    window.removeEventListener("click", this.menuTabs);
  },
};
</script>
