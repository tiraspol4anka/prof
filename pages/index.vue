<template>
  <div>
    <div class="top_line"></div>
    <BgroundLogo />
    <div class="container">
      <MainDescription
        :image-url="require('~/assets/images/check_box.jpg')"
        title="ТАКЕЛАЖНЫЕ УСЛУГИ ВЫСОКОГО КАЧЕСТВА"
        description="Для промышленных предприятий, в момент установки нового или перемещения существующего, часто стоит вопрос о привлечении такелажной компании для выполнения работ. Наличие многолетнего опыта позволяет нашей компании выполнять как самые простые, так самые сложные задачи по такелажным работам." />
      <MainDescription
        :image-url="require('~/assets/images/check_box.jpg')"
        title="ПОГРУЗОЧНО РАЗГРУЗОЧНЫЕ РАБОТЫ"
        description="Наша компания одновременно может выполнять от пяти заказов в день. Бригады снабжены всем необходимым оборудованием для реализации самых сложных задач по такелажу. Всегда в наличии бригада такелажников, которая готова оперативно выехать на объект и приступить к работам в течении 1,5 2-х часов." />
      <MainDescription
        :image-url="require('~/assets/images/check_box.jpg')"
        title="ПРОФЕССИОНАЛЬНАЯ УБОРКА ПОМЕЩЕНИЙ"
        description="Мы специализируемся на профессиональной уборке различных помещений. Мы внимательно изучим ваш объект, предложим варианты обслуживания и выполним работы качественно и быстро. Свыше 50% от общего числа наших клиентов мы обслуживаем на постоянной основе. Примерно 65% наших клиентов заключили с нами контракты по рекомендациям других клиентов. Мы работаем в строгом соответствии с законодательством РФ. Сотрудничество с нами является надежным и предсказуемым." />
      <MainDescription
        :image-url="require('~/assets/images/check_box.jpg')"
        title="ЛИЗИНГ ПЕРСОНАЛ"
        description="Подбираем и оперативно предоставляем специалистов для решения задач.
        Лизинг персонала - эффективный инструмент менеджмента. Он позволяет
        оптимизировать процессы кадрового делопроизводства, используя рабочую силу
        более гибко. Это достигается путем ее привлечения на условиях субподряда.
        Предприниматель заказывает у агенства услуги квалифицированного персонала
        для решения конкретных бизнес-задач. При этом не возникает необходимость
        оформлять и содержать персонал в постоянном штате компании. Услуги лизинга
        позволяют отптимизировать издержки, повысить эффективность управления
        кадрами. Они широко применяются в торговле, логистике, строительстве,
        юрисприденции, финансовой и других сферах." />
      <Staff
        text_item_first="Мы готовы обеспечить круглосуточный, посменный режим работы, гибкость и оперативность в предоставлении работников на постоянной основе и в
        периоды сезонных пиков, для выполнения непрофильных функций."
        text_item_second="Мы готовы взять на себя уборку территорий и вынос мусора; уборку
        помещений после строительства и ремонта; работы по благоустройству;
        земляные работы (копка ям, траншей, котлованов); прокладку кабелей,
        труб; дорожные работы, подсобные строительные работы; демонтажные
        работы, услуги по сортировке, маркировке, фасовке, упаковке и
        комплектации; разгрузочно-погрузочные работы." />
      <MainDescription
        :image-url="require('~/assets/images/check_box.jpg')"
        title="ВАКАНСИИ"
        description="Дворник, Уборщик, Грузчик, Подсобный рабочий, Мойщик посуды,
        Котломойщик." />
    </div>
    <FooterContext />
  </div>
</template>



<style>
html {
  background-color: #f4f4f4;
}

body {
  font-family: "Open Sans", sans-serif;
}

a {
  color: black;
  display: inline-block;
  text-decoration: none;
}

.container {
  background-color: white;
}

.top_line {
  height: 57px;
}

</style>
