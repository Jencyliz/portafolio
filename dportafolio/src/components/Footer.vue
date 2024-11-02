<template>
  <footer class="footer bg-info">
    <div class="footer-contenido">
      <div>
        <h2 class="text-white text-uppercase my-3 my-lg-4">Contacto</h2>
      </div>

      <div class="redes-sociales">
        <a
          href="https://github.com/Jencyliz"
          target="_blank"
          rel="noopener noreferrer"
        >
          <i class="fa-brands fa-github"></i>
        </a>
        <a
          href="https://www.linkedin.com/in/jency-ya%C3%B1ez-795030333/"
          target="_blank"
          rel="noopener noreferrer"
        >
          <i class="fa-brands fa-linkedin"></i>
        </a>
        <a
          href="https://www.youtube.com/watch?v=ZVe80q5gt1Q"
          target="_blank"
          rel="noopener noreferrer"
        >
          <i class="fa-brands fa-youtube"></i>
        </a>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  font-family: "Roboto", sans-serif;
  width: 100%;
  background-color: #333;
  padding: 0;
  margin: 0;
}

.footer-contenido {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.redes-sociales {
  display: flex;
  gap: 20px;
  justify-content: flex-end;
}

.redes-sociales a {
  color: white;
  font-size: 1.8em;
  transition: color 0.3s ease;
}

.redes-sociales a:hover {
  color: #cccccc;
}
</style>
