<template>
<nav class="navbar navbar-expand-md">
    <div class="container-fluid"> 
        <img src="https://i.postimg.cc/8zJVmgyS/rm-Hoodies.png" class="navLogo" >
    </div>
    <ul class="navIn ">
        <ul>
            <a href="/contact">Contact Us</a> 
        </ul>
    </ul>

  <div class="navIn mx-5">
    <ul>
      <ul><a href="/login">Login</a></ul>
    </ul>
  </div>
</nav>
</template>
<style>
:root {
    --color-primary: #50a117;
    --color-secondary: black;
    --color-white: #e3e8e3;
    --color-black: #030910;
    --color-dark: #1b5512;
    --color-gray: #7f9679;


    --font-Poppins: 'Poppins', sans-serif;
    --font-Raleway: 'Raleway', sans-serif;
    --font-OpenSans: 'Open Sans', sans-serif;

	--font-xlg: 90px;
    --font-lg: 64px;
    --font-md: 24px;
    --font-sm: 15px;
    --font-xs: 9px;

    --size-lg: 1280px;
    --size-md: 976px;
    --size-sm: 768px;
    --size-xs: 500px;
	--size-ms: 200px;
}
.navbar{
    background-color: var(--color-black);
    height:60px;
}
.navLogo{
    height:60px;
    width:65px;
}
.navIn{
    font-weight:bold;
    display:flex;
    justify-content:flex-end;
}
a:hover{
    color:var(--color-dark);
    text-decoration:none;
}
a{
    text-decoration:none;
    color:var(--color-primary);
}
</style>