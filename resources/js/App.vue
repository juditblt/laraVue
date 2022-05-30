<template>
    <br>
    <hr>
    Hello Mindenki!
    <hr>
    <CounterButton :startv="10" :min="1" :max="13"></CounterButton>
    <br>
    <!-- Így is lehet írni: -->
    <counter-button :startv="2"></counter-button>
    <br>
    <CounterButton :startv="0"></CounterButton>
    <hr>
    <br>
    <TemplateBox></TemplateBox>
</template>

<script>
import CounterButton from "./components/CounterButton";
import TemplateBox from "./components/TemplateBox";
export default {
    name: "App",
    components: {
        CounterButton,
        TemplateBox
    }
}
</script>

<style scoped>

</style>
