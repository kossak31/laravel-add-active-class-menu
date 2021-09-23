@php

$prefix = Request::route()->getPrefix();
$route = Route::current()->getName();

@endphp

<a href="" class="{{ $prefix == '/brand') ? 'active': '' }}">menu prefix</a>


<a href="" class="{{ $route == 'dashboard') ? 'active': '' }}">menu prefix</a>
