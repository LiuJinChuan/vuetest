<template>
    <div>
        <h1>这是 App 组件</h1>
        <router-link to="/login">登录</router-link>
        <router-link to="/register">注册</router-link>

        <router-view></router-view>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    
</style>

