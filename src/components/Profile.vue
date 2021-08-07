<template>

<section class="profile-section">
<img class="profleft" src="../assets/img/profright.svg"/>
<img class="profright" src="../assets/img/profleft.svg"/>
<div class="profile-content">

<div class="profile-top-row">
<!-- left avatar -->
<div class="avatar-left">
  <div class="mb-2">
    <b-avatar src="https://placekitten.com/300/300" size="6rem"></b-avatar>
    <b-button class="edit-avatar"><button class="btn-edit"></button><span>Edytuj zdjęcie</span></b-button>
  </div>

  </div>

  <div class="remove-right">
    <!-- Remove profile right -->
    
     <button class="btn-primary btn-remove">Usuń konto</button>
    
    </div>  
   
</div>


<form class="profile-data-row">
    
    <!-- User data -->
      <div class="prof-col">
      <h3>Dane użytkownika</h3>
      <!-- Name -->
      <label class="sr-only" for="inline-form-input-name">Imię</label>
       <b-form-input
       id="inline-form-input-name"
       class="flow-input"
       placeholder="Jane Doe"
    > </b-form-input>

   <!-- E-mail -->
   <label class="sr-only" for="inline-form-input-name">E-mail</label>
     
  <div class="mail-lock">
      <b-form-input
        class="flow-input"
        label="Email address:"
        label-for="input-1"
        description="We'll never share your email with anyone else.">
      </b-form-input>
         <button class="btn-lock"></button>    
     </div>
       </div>

     <!-- Additional info  -->
       <div class="prof-col">
       <h3>Dodatkowe informacje</h3>
       <!-- Date -->
       <label class="sr-only" for="inline-form-input-name">Data urodzenia</label>
        <b-form-input
        class="flow-input"
        placeholder="Data urodzenia"
      > </b-form-input>


        
       <!-- About me -->
       <label class="txtarea sr-only" for="inline-form-input-name">Coś o sobie…</label>
        <b-form-textarea
        id="textarea"
        v-model="text"
        placeholder="Enter something..."
        rows="3"
        max-rows="6"
    ></b-form-textarea>
<!-- Add button -->

<button class="btn-primary">Zapisz zmiany</button>
       </div>


<!-- Change password -->
      <div class="prof-col">
      <h3>Zmiana hasła</h3>
     <!-- Password -->
     <label for="text-password">Obecne hasło</label>
     <div class="input-eyepass">
     <b-form-input type="password" class="flow-input" aria-describedby="password-help-block"></b-form-input>
     <button class="btn-view"></button>
     </div>
     <!-- Password repeat -->
     <label for="text-password">Nowe hasło</label>
     <b-form-input type="password" class="flow-input" aria-describedby="password-help-block"></b-form-input>

    <!-- Add button -->
      <button class="btn-change btn-second">Zmień hasło</button>
       
 
       </div>

   </form>
   
  

</div>




</section>

</template>

<script>
  require('@/assets/css/profile/profile.scss') 
  export default {
    name: 'Profile',
  }
</script> 
