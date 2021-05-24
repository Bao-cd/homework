# homework
class homework
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <script src="vue.js"></script>
</head>
<body>
    <div id="app">
        <div v-if="isShow" style="background-color: #ccc;">我是bcd</div>
         <div v-if="isShow" style="background-color: #ccc;">I am your father</div>
          <button @click="isShow=!isShow">显示/隐藏</button>    
    </div>
    <script>
      var vm=new Vue({
          el:'#app',
          data:{
              isShow: true
          }
      })
    
    
    </script> 
</body>
</html>
