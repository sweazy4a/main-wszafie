<template>
  

  <div class="custom-row">


   <div class="buttons-only">
     <p>Primary</p>
     <button class="btn-primary">Button</button>
      <br>
      
     <p>Primary disabled</p>
     <button class="btn-primary btn-primary-disabled">Button</button>

      <br>
      <p>Seondary</p>
      <button class="btn-second">Button</button>
      
      <br>

      <p>Seondary disabled</p>
      <button class="btn-second btn-second-disabled">Button</button>
      
      <br>
      
      <p>Liked</p>
      <button class="btn-liked"></button>
   
      <br>
 
      <p>Disliked</p>
      <button class="btn-unliked"></button>

    <br>

     <p>Tag</p>
      <button class="bestseller">bestseller</button>


    <br>
    <br>


    <p>Profile</p>
    <button class="btn-birth"></button>


    <br>

    <button class="btn-wish"></button>
  
    <br>

    <button class="btn-gps"></button>
  
    <br>

    <button class="btn-edit"></button>

    <br>

    <button class="btn-view"></button>

    <br> 

    <button class="btn-lock"></button>

   </div>


<br>
<br>

   <div class="alerts-only">

    <p>Alerts</p>
     <div class="alert-failed">
        <div class="acontent">
           <strong>Formularz nie został wysłany</strong>
           <p>Sprawdź, lorem ipsum dolor sit amet consce ntetur adipiscing elit</p>
        </div>
     </div>
    <br>
    <div class="alert-success">
        <div class="acontent">
           <strong>Wiadomość została wysłana</strong>
           <p>Dziękujemy za wieści od Ciebie. Lorem ipsum dolor</p>
        </div>



     </div>
  
   </div>
<br>
<br>
  <p>Inputs</p>
   <div class="inputs-only" style="width:300px;">
     <label class="sr-only" for="inline-form-input-name">E-mail</label>
     <b-form-input
        class="flow-input"
        label="Email address:"
        label-for="input-1"
        description="We'll never share your email with anyone else.">
  </b-form-input>

   <br>

    <p>Disabled</p>
     <b-form-input
        class="flow-input flow-input-disabled"
        label="Email address:"
        label-for="input-1"
        description="We'll never share your email with anyone else.">
  </b-form-input>
   <br>

     <p>Error</p>
     <b-form-input
        class="flow-input flow-input-error"
        label="Email address:"
        label-for="input-1"
        description="We'll never share your email with anyone else.">

</b-form-input>
<p class="flow-input-error-message">Niepoprawny format adresu email</p>



   <br>
      <br>

   </div>


</div>



</template>
<script>

  export default {
    name: 'Elements',
  }

</script> 
