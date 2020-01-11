<template>
     
    <div class="header" >
     <h5>易安网(北京)科技有限公司</h5>
      <div class="box">
      <h2>易安防管理系统</h2>
       <span>用户名：</span><input type="text"   placeholder="手机号/用户名">
      <span>密码： </span><input type="password" placeholder="密码">
       <button @click="click">登录</button>
     </div>
      
    

    </div>
</template>

<script>

    export default {
        //  data(){
        // return {
        //     val:''
        // } 
    
//  methods:{
//         // click(){
		   
//         //             if(data.code === 0){
//         //                 this.$router.push('/');
//         //             }else{
//         //                 alert('登录失败');
//         //             }
//         //             this.val = '';
                
//         // }
//     }  



    }
</script>

<style scoped>
.header{
    width:100%;
    height:100%;
    border:1px solid black;
    text-
}
h5{
   color:black; 
   width:30%;
   margin-left:70%;
   color:white;
   border:1px solid black;
}
.box{
    width:400px;   
    border:1px solid black;  
    background:gray; 
}

h2{
    width:80%;
	border:1px solid black;
	background: rgba(0, 0, 0, 0.003);
	box-shadow: inset 0 -2px 1px rgba(0,0,0,0.03);
    height:50px;   
    display:flex;  
}
input{
    display:flex;
    height:30px;
    margin-bottom:15px;
}
button{
     width:80%;
     background:skyblue;
     height:30px;
}

</style>