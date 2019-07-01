<template>
  <section class="contact">
    <div class="contact__wrap">
      <div class="contact__title">  
        <h3>Contact us</h3>
      </div>
      <div class="contact__forms">
        <form id="contact-form"  method="POST" action="/contact">
          <div class="fw contact__inputs">
            <div class="contact__input">
              <label for="name">Your name</label>
              <input id="name" name="name" type="text"> 
            </div>
            <div class="contact__input">
              <label for="email">Email</label>
              <input id="email" name="email" type="email"> 
            </div>
          </div>
          <div class="contact__input">
            <label for="message">Text message</label>
            <input id="message" name="message" type="text"> 
          </div>
          <div class="contact__btn">
            <button>Send</button>
          </div>
        </form>
      </div>
    </div>
  </section>
</template>
