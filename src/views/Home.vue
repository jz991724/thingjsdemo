<template>
    <div class="home">
<!--        <img alt="Vue logo" src="../assets/logo.png"/>-->
        <!--    <HelloWorld msg="Welcome to Your Vue.js App" />-->
        <ThingJs></ThingJs>
    </div>
</template>

<script lang="ts">
    import {Vue, Component} from "vue-property-decorator";

    // @ is an alias to /src
    import HelloWorld from "@/components/HelloWorld.vue";
    import ThingJs from "@/components/ThingJs.vue";

    @Component({
        components: {
            ThingJs
        }
    })
    export default class Home extends Vue{
        name: string = "home"
    };
</script>
