<template>
  <div>
 <header>
      <div class="row">
    <nav class="navbar navbar-expand-lg navbar-light fixed-top" style="background: transparent;">
    
      <div class="col-6 offset-lg-1 col-lg-4">
      <a class="navbar-brand" href="#"><img src="../assets/imgs/logo.png" class="brand img-fluid" alt=""></a>
      </div>

      
      <button class="navbar-toggler col-2" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      

      <div class="col-lg-6">

        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item mr-5">
              <a class="nav-link" href="#">sobre <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item mr-5">
              <a class="nav-link" href="#">blog</a>
            </li>
            <li class="nav-item mr-5">
              <a class="nav-link" href="#">suporte</a>
            </li>
            <li class="nav-item active mr-5">
              <a class="nav-link" href="#">login</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#">cadastrar</a>
            </li>
          </ul>
        </div>
      </div>
    
    </nav>
    </div>
    </header>
    <div class="apresentacao container-fluid">
      <div class="row justify-content-center">
        <div class="col-lg-5" style="margin-top: 250px;">
          <h1 style="color: white;">MELHORE OS<br>
           SEUS ENVIOS</h1>
           <h5 style="color: white;">
            Somos uma plataforma de intermediação <br>
           de fretes, conectando clientes e transportadoras.</h5>
           <button type="button" class="btn btn-light"><b style="color:#044d9d;">DÊ O PRIMEIRO PASSO</b></button>
        </div>
        <div class="col-lg-5" style="margin-top: 140px;">
          <img src="../assets/imgs/caixa.png" alt="" class="img-fluid">
        </div>
      </div>
    </div>
    <div class="container-fluid">
    <div class="row justify-content-center margin-t">
      <div class="col-lg-6 txt-centro" style="margin-bottom:50px;"><h5>transportadoras</h5>
      <img src="../assets/imgs/01t.png" class="img-fluid margin-l mt-3" alt="">
        <img src="../assets/imgs/02t.png" class="img-fluid margin-l mt-3" alt="">
        <img src="../assets/imgs/03t.png" class="img-fluid margin-l mt-3" alt="">
        <img src="../assets/imgs/04t.png" class="img-fluid margin-l mt-3" alt="">
      </div>
      <div class="col-lg-6 txt-centro"><h5>parceiros</h5>
      <img src="../assets/imgs/01p.png" class="img-fluid margin-l mt-3" alt="">
        <img src="../assets/imgs/02p.png" class="img-fluid margin-l mt-3" alt="">
        <img src="../assets/imgs/03p.png" class="img-fluid margin-l mt-3" alt="">
        <img src="../assets/imgs/04p.png" class="img-fluid margin-l mt-3" alt="">
        <img src="../assets/imgs/05p.png" class="img-fluid margin-l mt-3" alt="">
      </div>
    </div>
</div>

  <div class="container-fluid shadow-t">
    <div class="container" style="padding-top: 100px;">
    <h1 style="text-align: center;">Calculadora de</h1>
    <p style="text-align: center;">Insira os dados do seu envio e compare cotações a preços exclusivos, Vá em frente, é simples.</p>


    <form>
      <div class="form-row justify-content-between" style="align-items: center;">
        <div class="form-group col-lg-4">
          <label for="cepOrigem">CEP de Origem</label>
          <input type="text" class="form-control form-control-lg">
        </div>
        <div>
          <img src="../assets/imgs/seta.png" class="img-fluid" alt="">
        </div>
        <div class="form-group col-lg-4">
          <label for="cepDestino">CEP de Destino</label>
          <input type="text" class="form-control form-control-lg">
        </div>
      </div>

      <div class="form-row justify-content-between" style="align-items: center;">
        <div class="form-group col-lg-2 mx-0">
          <label for="altura">Altura</label>
          <input type="text" class="form-control form-control-lg">
        </div>
        <div class="form-group col-lg-2 mx-0">
          <label for="largura">Largura</label>
          <input type="text" class="form-control form-control-lg">
        </div>
        <div class="form-group col-lg-2 mx-0">
          <label for="comprimento">Comprimento</label>
          <input type="text" class="form-control form-control-lg">
        </div>
        <div class="form-group col-lg-2 mx-0">
          <label for="peso">Peso</label>
          <input type="text" class="form-control form-control-lg">
        </div>
        <div class="form-group col-lg-2 mx-0">
          <label for="valor">Valor</label>
          <input type="text" class="form-control form-control-lg">
        </div>
      </div>
      <div class="form-row justify-content-center my-4">
      <button type="button" class="btn btn-primary btn-lg px-5">Calcular</button>
      </div>
    </form>
    </div>
  </div>

  <div class="container-fluid pb-5" style="background-color: #26303c">
    <div class="row justify-content-center">
      <div class="col-lg-2 mt-5">
        <h5 style="color: white;"><b>Sediada no</b></h5>
        <img src="../assets/imgs/parque.png" alt="" class="img-fluid">
      </div>
      <div class="col-lg-4 mt-5">
        <h5 style="color: white;"><b>Acelerada por</b></h5>
        <img src="../assets/imgs/ace.png" alt="" class="img-fluid margin-l">
      
        <img src="../assets/imgs/startup.png" alt="" class="img-fluid margin-l">

        <img src="../assets/imgs/startups.png" alt="" class="img-fluid margin-l">

        <img src="../assets/imgs/scale.png" alt="" class="img-fluid margin-l">

        <img src="../assets/imgs/inovativa.png" alt="" class="img-fluid margin-l">
      </div>
    </div>

    <div class="row justify-content-center ml-5">
      <div class="col-lg-2 mt-5">
        <h5 style="color: white;"><b>Incubada</b></h5>
        <img src="../assets/imgs/ciemsul.png" alt="" class="img-fluid">
      </div>
      <div class="col-lg-4 mt-5">
        <h5 style="color: white;"><b>Investida</b></h5>
        <img src="../assets/imgs/ace.png" alt="" class="img-fluid margin-l">
      
        <img src="../assets/imgs/sebrae.png" alt="" class="img-fluid margin-l">

        <img src="../assets/imgs/bossanova.png" alt="" class="img-fluid margin-l">
      </div>
    </div>
  </div>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
