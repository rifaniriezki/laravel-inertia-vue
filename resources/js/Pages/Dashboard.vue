
<template>
    <div>
        <p class="p-4 bg-green-200">{{ $page.props.flash.greet }}</p>
        <h1>
            Dashboard
        </h1>
        <h2 class="title">Terima Kasih {{ $page.props.auth.user.name }}</h2>
    </div>
</template>
