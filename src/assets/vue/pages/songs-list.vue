<template>
  <f7-page>
    <f7-navbar title="Список всех песен" back-link="Back" sliding></f7-navbar>
    <f7-list>
      <!--
      <f7-list-item link="/about/" title="About" panel-close></f7-list-item>
      <f7-list-item link="/form/" title="Form" panel-close></f7-list-item>-->
      <f7-list-item link="/songs/song-001/" title="001. Аллилуя, аллилуя" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-002/" title="002. Аллилуя" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-003/" title="003. Бесценный дар любви" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-004/" title="004. Благодарю, Создатель мой" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-005/" title="005. Бога я вижу" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-006/" title="006. Бог любви" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-007/" title="007. Боже, спасибо" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-008/" title="008. Божий дизайн" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-009/" title="009. Будь верен в испытаниях" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-010/" title="010. В белом облаке" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-011/" title="011. Велики и чудны" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-012/" title="012. Верю я" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-013/" title="013. В жизни надо успеть" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-014/" title="014. В кладезях Библии" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-015/" title="015. Вместе мы с тобой" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-016/" title="016. В небесных доспехах" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-017/" title="017. Во всеоружии" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-018/" title="018. Возношу свои руки к небу" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-019/" title="019. В ослепительном свете" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-020/" title="020. Время не ждёт" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-021/" title="021. Время не теряй" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-022/" title="022. Все молитвы сердца" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-023/" title="023. Вся слава Тебе!" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-024/" title="024. В это верю я" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-025/" title="025. В этот час преклоню колени я" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-026/" title="026. Гимн лагеря 2014: К дальним берегам" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-027/" title="027. Гимн радуга 2015" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-028/" title="028. Гимн радуга 2016" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-029/" title="029. Город моей мечты" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-030/" title="030. Господь – мой Добрый Пастырь" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-031/" title="031. Господь - мой спаситель" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-032/" title="032. Граждане неба" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-033/" title="033. Давайте за руки возьмемся" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-034/" title="034. Дай мне руку, друг" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-035/" title="035. День за днём" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-036/" title="036. Ему имя - Чудный" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-037/" title="037. Если грех тебя теснит" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-038/" title="038. Если рядом друг" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-039/" title="039. Если утром солнышко светит" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-040/" title="040. Здесь мои друзья" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-041/" title="041. Здравствуй, Суббота!" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-042/" title="042. Иисус, спасибо" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-043/" title="043. Иисус тебя любит" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-044/" title="044. Каждый день, просыпаясь" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-045/" title="045. Как прекрасен рассвет" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-046/" title="046. Как приятно, как чудесно" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-047/" title="047. Кистью Творца" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-048/" title="048. Книга книг" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-049/" title="049. Книжный червячок" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-050/" title="050. Когда болит твоя душа" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-051/" title="051. Когда любовь приходит с неба" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-052/" title="052. Когда мы вместе" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-053/" title="053. Кораблик бумажный" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-054/" title="054. Кто зажигает солнце?" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-055/" title="055. Куда б мы ни ехали" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-056/" title="056. Ликуйте, братья, ликуйте, сёстры!" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-057/" title="057. Ликуйте небеса" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-058/" title="058. Лицом к лицу" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-059/" title="059. Лучший Друг" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-060/" title="060. Милости Твоей" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-061/" title="061. Мне бы крылья!" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-062/" title="062. Много километров" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-063/" title="063. Мой Господь, в этот час" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-064/" title="064. Мы вместе сегодня" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-065/" title="065. Мы воспоем Тебе сегодня гимн" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-066/" title="066. Мы дети Божьи" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-067/" title="067. Мы живём, как на вулкане" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-068/" title="068. Мы одна семья" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-069/" title="069. Мы одно тело" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-070/" title="070. Найди свой путь" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-071/" title="071. Нам нужны друзья" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-072/" title="072. На рассвете" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-073/" title="073. На середине пути" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-074/" title="074. Нас ждут" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-075/" title="075. На скрижалях сердца" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-076/" title="076. Настоящий Человек/Бог" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-077/" title="077. Начиная новый день" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-078/" title="078. Наш Бог – Всемогущий Бог" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-079/" title="079. Небеса (Гимн)" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-080/" title="080. Небесный Дом" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-081/" title="081. Небо, синее небо" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-082/" title="082. Нет никого, как Ты" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-083/" title="083. О, великий Бог" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-084/" title="084. Оглянись вокруг" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-085/" title="085. Омой меня" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-086/" title="086. Он был, Он есть" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-087/" title="087. Он ждёт тебя!" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-088/" title="088. Он мой друг" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-089/" title="089. Он придёт" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-090/" title="090. Осанна" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-091/" title="091. Оставь свои заботы" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-092/" title="092. Отдай таланты ты Богу" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-093/" title="093. От сердца к сердцу" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-094/" title="094. Отче, мы просим" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-095/" title="095. Паруса надежды" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-096/" title="096. Песня о друге" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-097/" title="097. Пилигрим" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-098/" title="098. Покорители мира" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-099/" title="099. Посмотри на небо" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-100/" title="100. Приношу Христу я хвалу" panel-close></f7-list-item>
      <f7-list-item link="/songs/song-101/" title="101. Приходи Иисус" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-102/" title="102. Прихожу прославить" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-103/" title="103. Про принцев и принцесс" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-104/" title="104. Прорастая сквозь асфальт" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-105/" title="105. Прославлю Бога за любовь" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-106/" title="106. Просыпаюсь на заре" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-107/" title="107. Пустыня" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-108/" title="108. Путь, истина, жизнь" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-109/" title="109. Радость в сердце" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-110/" title="110. Разбитые сосуды (о благодать)" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-111/" title="111. Раскрась свой мир" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-112/" title="112. Река" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-113/" title="113. Свечи зажжём" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-114/" title="114. Святый" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-115/" title="115. Сейнт Оливер" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-116/" title="116. Сияй, Иисус, сияй" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-117/" title="117. Скоро рассвет" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-118/" title="118. Слепой стоял у дороги, прося" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-119/" title="119. Слово" panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-120/" title="120. Смолкли звуки дня" panel-close></f7-list-item>  
      <br><br><br>      
      <!--
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  
      <f7-list-item link="/songs/song-10/" title="10. " panel-close></f7-list-item>  

      -->
      <!--
      <f7-list-item link="/songs/song-051/" title="061. " panel-close></f7-list-item>
      -->
    </f7-list>
  </f7-page>
</template>
<script>
export default {};
</script>
