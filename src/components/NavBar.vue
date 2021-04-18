<template>
    <nav class="navbar navbar-expand-lg navbar-light navbar-fixed-top">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
            <img src="/images/logo.svg" alt="" width="50" height="50">
            Relab
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">中文</a>
            </li>
          </ul>
        </div>
        <div class="d-flex">
            <a class="btn btn-primary btn-trial">Free Trial</a>
            <a class="btn btn-primary btn-login">Login</a>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
    name: 'NavBar',
}
</script>

<style scoped>
.navbar {
    font-weight: bold;
    z-index: 1030;
}
.nav-item {
    font-size: 1rem;
}
.navbar-brand {
    color: #23b5af !important;
    margin-right:25px;
}
.btn {
    margin-left: 15px;
}
.btn-trial {
    color: #fff;
    background-color: #ff0c7d;
    border-color: #ff0c7d;
}
.btn-login {
    color: #fff;
    background-color: #23b5af;
    border-color: #23b5af;
}
</style>