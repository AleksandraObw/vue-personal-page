<script>
import emailjs from '@emailjs/browser';

export default {
  methods: {
    sendEmail() { 
      emailjs
        .sendForm('service_h2jwxw2', 'template_lwax7e7', this.$refs.form, {
          publicKey: 'saevIdYZ0KCw8s2GT',
        })
        .then(
          () => {
            alert('Message is successfully sent!');
            this.$refs.form.reset();
          },
          (error) => {
            alert('Message sending failed! '); 
            console.log(error.text);
          },
        );
    },
  },
};
</script>

<template>
    <div>
      <h1>Contacts</h1>
      <form ref="form" @submit.prevent="sendEmail" class="contacts_form">
            <label>Name</label>
            <input type="text" name="from_name" required autocomplete=none> 
            <label>Email</label>
            <input type="email" name="from_email" required autocomplete="email">
            <label>Message</label>
            <textarea name="message" required placeholder="Enter your message here... | Введите свое сообщение..."></textarea>
            <input type="submit" value="Send">
      </form>
    </div>
  </template>
  
  <style scoped>
    div {
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .contacts_form {
        display: flex;
        flex-direction: column;
        align-items: start;
        justify-content: center;
        row-gap: 8px;
        width: max(50%, 300px);
    }
    input {
        width: 100%;
        height: 3em;
        padding: .5em;
        font-size: 1em;
        border-color: #018185;
    }
    textarea {
        width: 100%;
        height: 10em;
        padding: .5em;
        font-size: 1.2em;
        resize: none;
        border: 2px solid #018185;
    }
    label {
        font-weight: bolder;
        margin-top: 1em;
    }
    input[type="submit"] {
        margin-top: 1em;
        font-weight: bold;
        background-color: #018185;
        background-image: linear-gradient(-60deg, transparent 0%, transparent 40%, #ffffff44 40%, #ffffff44 60%, transparent 60%, transparent 100%);
        background-size: 200% 100%;
        background-repeat: no-repeat;
        color: #ffffff;
        border: none;
        cursor: pointer;
        transition: all .5s ease-in-out;
        background-position-x: 150%;
    }
    input[type="submit"]:hover {
        box-shadow: inset 0 0 2px 2px #00b3b9;
        box-shadow: 0 0 2px 2px #00b3b9;
        background-position-x: -150%;
        transition: background-position-x 1000ms;
    } 
  </style>

    
