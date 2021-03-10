<template>
    <div>
        <Topnav/>
        <div class="content">
        <aside>
            <h2>组件列表</h2>
            <ol>
                <li>
                   <router-link to="/doc/switch">Switch 组件</router-link>
                </li>
                <li>
                    <router-link to="/doc/button">Button 组件</router-link>
                </li>
                <li>
                    <router-link to="/doc/dialog">Dialog 组件</router-link>
                </li>
                <li>
                    <router-link to="/doc/tabs">Tabs 组件</router-link></li> 
            </ol>
        </aside>
        <main>主内容</main>
    </div>
    </div>
    
</template>

<script lant="ts">
import Topnav from '../components/Topnav.vue'
export default {
    components:{Topnav}
}
</script>
<style lang="scss" scoped>
    .banner {
        padding: 100px 0;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background: lightgreen;
        > .actions{
            padding: 8px 0;
            a {
            margin:0 8px;
            background: #fff;
            display: inline-block;
            $h: 28px;
            height: $h;
            line-height: $h;
            border-radius: $h/2;
            padding: 0 8px;
            }
        }
    }
</style>