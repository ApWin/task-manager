<template>
    <div class="hello">

    </div>
</template>

<script>

    export default {
        name: 'HelloWorld',

        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h3 {
        margin: 40px 0 0;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }

    a {
        color: #42b983;
    }
    .status {
      border-bottom: 1.5px solid #d8d8d8;
      color: #0e4d3d;
      font-weight: 700;
      padding: 10px;
    }
    .el-card {
      border: 1px solid #ebeef5;
      background-color: #fff;
      color: #303133;
      -webkit-transition: .3s;
      transition: .3s;
    }
</style>
