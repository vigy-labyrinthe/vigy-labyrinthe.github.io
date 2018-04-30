---
title: Nous contacter
permalink: contact.html
layout: page
---



<style>
input[type=text], input[type=email], select {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
}

input[type=submit] {
    width: 100%;
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

input[type=submit]:hover {
    background-color: #45a049;
}

form {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
}
</style>


<form action="https://formspree.io/vigy-labyrinthe@orange.fr"
      method="POST">
    <input type="hidden" name="_language" value="fr" />
    
    <label for="name">Votre nom</label> 
    <input type="text" name="name">
    
    <label for="_replyto">Votre adresse email</label> 
    <input type="email" name="_replyto">
    
    <label for="_subject">Sujet</label>
    <input type="text" name="_subject">
    
    <label for="message">Message</label>
    <textarea name="message" rows="10" col="50"></textarea>
    
    <input type="submit" value="Envoyer">
</form>
