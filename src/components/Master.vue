<!--HTML-->
<template>
    <div>
        <!--header-->
        <Navbar/>
        <Sidebar/>

        <!--contents slot-->
        <!-- <slot name="contents"></slot> -->

        <!--footer-->
        
    </div>
</template>


<!--JS-->
<script>
    import Sidebar from "./partials/Sidebar";
    import Navbar from "./partials/Navbar";

    export default {
        name: "Master",
        components: {Navbar,Sidebar},
    }
</script>


<!--CSS-->
<style scoped></style>

