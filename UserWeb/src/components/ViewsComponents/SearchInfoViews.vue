<template>
    <div class="container">
        <div>
            <TopBack
            title="搜索" 
            :iconSize="27"
            navBarHeight="47px"/>
        </div>
            <div class="search">
                <Search/>
            </div>
            <div>
                标签：//待开发{{ "WFB" }}
            </div>
    </div>
</template>
<script setup>
import TopBack from '@/components/FuntionComponents/TopBack.vue';
import Search from '../Index/Search.vue';

</script>