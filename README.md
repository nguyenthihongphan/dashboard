# dashboard
<!DOCTYPE html>
 <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
        <title>Project-Phan</title>

<x-app-layout>
    <x-slot name="header">
        <h2 class="font-semibold text-xl text-gray-800 leading-tight">
            {{ __('intern-hphan') }}
        </h2>
    </x-slot>
    <body>
    <div class="container">
    <div class="menu border-right col-lg-2">
  <ul class="nav flex-column col-md-2">
  <li class="nav-item btn btn-light menu_li">
    <a class="nav-link disabled active" href="#">Users</a>
  </li>
  <li class="nav-item btn btn-light menu_li">
    <a class="nav-link disabled " href="#">Product</a>
  </li>
  <li class="nav-item btn btn-light menu_li">
    <a class="nav-link disabled" href="#">Categories</a>
  </li>
  <li class="nav-item btn btn-light menu_li">
    <a class="nav-link disabled" href="#">Orders</a>
  </li>
</ul>
    </div>
    <div class="content">

    </div>
    </div>
    </body>
  <footer class="bg-light text-center text-lg-start">
  <!-- Copyright -->
  <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
    © 2022 Copyright:
    <a class="text-dark" href="https://mdbootstrap.com/">Hongphan</a>
  </div>
  <!-- Copyright -->
</footer>  
</x-app-layout>
<style>
.menu_li{
    margin-top:10px;
}
.menu {
    border-right:3px solid grey;
    height:500px;
}
.footer{
    background-color:black;
    width:100px
}
</style>
