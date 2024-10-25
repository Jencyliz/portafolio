<template>
    <section id="contact" class="my-5">
      <h2>Contacto</h2>
      <form>
        <div class="form-group">
          <label for="name">Nombre</label>
          <input type="text" class="form-control" id="name" placeholder="Tu nombre">
        </div>
        <div class="form-group">
          <label for="email">Correo electrónico</label>
          <input type="email" class="form-control" id="email" placeholder="Tu correo">
        </div>
        <div class="form-group">
          <label for="message">Mensaje</label>
          <textarea class="form-control" id="message" rows="3" placeholder="Tu mensaje"></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Enviar</button>
      </form>
    </section>
  </template>
  