<template>
  <router-view/>
    <h2>クイズ</h2>
    <div><input type="text"></div>
    <div><textarea></textarea></div>
    <div class="center">
        <button>保存</button>
    </div>
    <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">Result</router-link>
  </nav>
</template>