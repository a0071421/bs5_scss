<template>
  <header class="header border-bottom border-primary border-4">
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container">
        <h1 class="logo me-5">
          <a class="navbar-brand bg-cover" href="#">拚拚</a>
        </h1>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item me-5">
              <a class="nav-link active" aria-current="page" href="#">關於</a>
            </li>
            <li class="nav-item me-5">
              <a class="nav-link" href="#">挖寶</a>
            </li>
            <li class="nav-item me-5">
              <a class="nav-link" href="#">我有個大膽的想法</a>
            </li>
          </ul>
          <div>
            <button
              class="btn btn-primary px-4 me-3 fw-bold rounded-pill"
              data-bs-toggle="modal"
              data-bs-target="#login"
            >
              登入
            </button>
            <button class="btn btn-outline-secondary fw-bold px-4 rounded-pill">
              註冊
            </button>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>
