<template>
    <div class="">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Sudoku</a>
        <!-- toggle navigation - check if needed -->
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
                <RouterLink to="/">
                    <a class="nav-link active" aria-current="page">Home</a>
                </RouterLink>
            </li>
            <li class="nav-item">
                <RouterLink to="/">
                    <a class="nav-link" href="#">Solve</a>
                </RouterLink>
            </li>
            <li class="nav-item">
                <RouterLink to="/">
                    <a class="nav-link" href="#">Generate</a>
                </RouterLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    </div>
</template>

<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: "navbar" //,

    // data() {
    //     return {
    //         items: [
    //             { name: "Home", link: "/", icon: "fa-solid fa-house" },
    //             { name: "Education", link: "/education", icon: "fa-book-open" },
    //             { name: "Experiences", link: "/experience", icon: "fa-calendar-day" },
    //             { name: "Projects", link: "/projects", icon: "fa-laptop-code" }
    //         ]
    //     }
    // }
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
}

body {
    margin-top: 0 !important;
}

.navbar a {
    color: whitesmoke;
    font-size: 20px !important;
}

.navbar {
    background-color: rgba(0, 0, 0, .3) !important;
}
</style>
