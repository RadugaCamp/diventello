<template>
    <f7-page>
        <f7-navbar>
            <f7-nav-left>
                <f7-link class="panel-open" open-panel="left" icon="fa fa-music"></f7-link>
            </f7-nav-left>
            <div class="title">Diventello : Становление</div>
            <!--
            <f7-nav-right>
                <f7-link class="searchbar-enable" data-searchbar=".searchbar-components" icon="fa fa-search"></f7-link>
            </f7-nav-right>
            <f7-searchbar class="searchbar-components" search-container=".components-list" search-in="a" expandable></f7-searchbar>-->
        </f7-navbar>
        <!--
        <f7-block-title> "Песни Радуга 20 лет"</f7-block-title>-->
        <f7-block inner>
            <p></p>
        </f7-block>
        <!--
        <f7-block-title class="searchbar-found">Links</f7-block-title>-->
        <f7-block>
            <f7-list class="components-list searchbar-found">
                <f7-list-item>
                    <div class=".logo__home">
                        <img class="" src="../../images/raduga-logo-200x200px.png" >
                    </div>
                </f7-list-item>
            </f7-list>
        </f7-block>

        <br><br>

        <f7-list class="components-list">
            <f7-list-item link="/songs-list/" title="Список всех песен" panel-close>
                <f7-icon slot="media" icon="fa fa-music fa-fw"></f7-icon>
            </f7-list-item>
        </f7-list>
    </f7-page>
</template>
<script>
export default {};

</script>

<style>
.logo__home {
  position: absolute;
  left: 50%;
  top: 50%;
}
</style>
