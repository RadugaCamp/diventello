<template>
  <f7-page>
    <f7-block-title><strong>СОДЕРЖАНИЕ</strong></f7-block-title>
    <f7-block>
      <p>В сборник вошли любимые песни, исполняемые в лагере "Радуга" за прошедшие 20 лет (1999...2018)<!--<f7-link panel-close>close me</f7-link>. You can put here anything.--></p>
      <p>Песни размещены не погодам, а в алфавитном порядке.</p>
    </f7-block>
    <f7-list class="components-list">
      <f7-list-item link="/songs-list/" title="Список всех песен" panel-close>
        <f7-icon slot="media" icon="fa fa-music fa-fw"></f7-icon>
      </f7-list-item>
      <f7-list-item link="/about/" title="О приложении" panel-close>
        <f7-icon slot="media" icon="fa fa-info fa-fw"></f7-icon>
      </f7-list-item>
      <f7-list-item><p><strong>Доступны песни</strong> <mark>1-120</mark></p></f7-list-item>
      <f7-list-item>
        <!-- Button send review-->
        <div>
          <div>
            <p align="center">
              <a class="link external" href="https://play.google.com/store/apps/details?id=ru.raduga.diventello">
              <button class="col button button-fill button">Написать отзыв</button>
            </a>
            </p>
          </div>
        </div>
        <!-- /END Button send review-->
      </f7-list-item>
      <f7-list-item>ver. 1.0.7</f7-list-item>
    </f7-list>

    <f7-list>

    </f7-list>
  </f7-page>
</template>
<script>
export default {};
</script>
