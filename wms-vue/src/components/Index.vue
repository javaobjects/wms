<template>
    <el-container style="height: 100%; border: 1px solid #eee">
        <el-aside :width="aside_witdh" style="height: 100vh;background-color: rgb(238, 241, 246);margin-left: -1px;">
            <Aside :isCollapse="isCollapse"></Aside>
        </el-aside>

        <el-container style="height: 100%;">
            <el-header style="text-align: right; font-size: 12px;height: 100%;border-bottom: rgba(168,168,168,0.3) 1px solid;">
                <Header @doCollapse="doCollapse" :icon="icon"></Header>
            </el-header>

            <el-main style="height: 100%;">
               <!-- <Main></Main>-->
                <router-view/>
            </el-main>
        </el-container>
    </el-container>
</template>

<script>
    import Aside from "./Aside";
    import Header from "./Header";

    export default {
        name: "Index",
        components:{Aside,Header},
        data(){
            return {
                isCollapse:false,
                aside_witdh:'200px',
                icon:'el-icon-s-fold'
            }
        },
        methods:{
            doCollapse(){
                console.log(1111)

                this.isCollapse = !this.isCollapse
                if(!this.isCollapse){// 展开
                    this.aside_witdh='200px'
                    this.icon='el-icon-s-fold'
                }else{//关起、关闭、收起
                    this.aside_witdh='64px'
                    this.icon='el-icon-s-unfold'
                }
            }
        }
    }
</script>

<style scoped>
    .el-header {
        #background-color: #B3C0D1;
        color: #333;
        line-height: 60px;
    }
    .el-main{
        padding: 5px;
    }
    .el-aside {
        color: #333;
    }
</style>