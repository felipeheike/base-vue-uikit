<template>
  <div class="uk-panel uk-margin-large">
    <nav class="uk-navbar-container uk-margin" uk-navbar>
      <div class="uk-navbar-center">
          <svg  width="32" height="38" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="vuejs" class="svg-inline--fa fa-vuejs fa-w-14" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
            <path fill="#4fc08d" d="M356.9 64.3H280l-56 88.6-48-88.6H0L224 448 448 64.3h-91.1zm-301.2 32h53.8L224 294.5 338.4 96.3h53.8L224 384.5 55.7 96.3z"></path>
          </svg>
          <h1><a class="uk-navbar-item uk-logo" href="#">Vue + Uikit</a></h1>
          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="34" viewBox="0 0 28 34">
	          <polygon fill="#39f" points="19.1,4.1 13.75,1 8.17,4.45 13.6,7.44 "/>
          	<path fill="#39f" d="M21.67,5.43l-5.53,3.34l6.26,3.63v9.52l-8.44,4.76L5.6,21.93v-7.38L0,11.7v13.51l13.75,8.08L28,25.21V9.07 L21.67,5.43z"/>
            </svg>
      </div>
    </nav>
    <h1 class="uk-heading uk-text-center">{{msg}}</h1>
    <div class="uk-child-width-1-3@m uk-grid-small uk-grid-match uk-panel uk-padding" uk-grid>
        <div>
            <div class="uk-card uk-card-primary  uk-card-body" style="background-color:#4fc08d;">
                <h3 class="uk-card-title">Doc. Vue</h3>
                <p>Acesse a página oficial que contém documentação e material de apoio do Vue.js.</p>
                <a class="uk-button uk-button-default uk-button-small" href="https://vuejs.org/">Acessar</a>
            </div>
        </div>
        <div>
            <div class="uk-card uk-card-primary uk-card-body">
                <h3 class="uk-card-title">Doc. Uikit</h3>
                <p>Acesse a página oficial que contém documentação, visualização e testes dos componentes do Uikit .</p>
                <a class="uk-button uk-button-default uk-button-small" href="https://getuikit.com/">Acessar</a>
            </div>
        </div>
        <div>
            <div class="uk-card uk-card-secondary uk-card-body">
                <h3 class="uk-card-title">Github instructions</h3>
                <p>Acesse este link para ter acesso ao nosso projeto e consultar as instruções que colocamos no Github.</p>
                <a class="uk-button uk-button-default uk-button-small" href="https://github.com/felipeheike/base-vue-uikit">Acessar</a>
            </div>
        </div>
    <div class="uk-grid-medium uk-child-width-expand@s uk-text-center uk-align-center">
        <button class="uk-button uk-button-default uk-margin-small" type="button" uk-toggle="target: #offcanvas-usage">Integrantes</button>

        <div id="offcanvas-usage" uk-offcanvas>
            <div class="uk-offcanvas-bar">

                <button class="uk-offcanvas-close" type="button" uk-close></button>

                <h3>Integrantes do seminário</h3>

                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>

            </div>
        </div>
    </div>
    </div>
  </div>
</template>

<script>
import UIkit from "../../node_modules/uikit/dist/js/uikit";
export default {
  name: "hello",
  data() {
    return {
      msg: "Hello Word!",
      integrantes: ""
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>


