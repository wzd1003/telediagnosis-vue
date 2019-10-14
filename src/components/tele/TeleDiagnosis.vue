<template>
  <div>
    <h1 id="app">进入会诊房间</h1>
    请输入姓名：<input id="name" type="text"> <br><br>
    请输入id号：<input id="id" type="number"><br><br>
    请选择创建房间的类型：<select id="ty">
    <option value="conference">会议房间</option>
    <option value="presentation">演示房间</option>
    <option value="interview">面试房间</option>
  </select><br><br>
    请输入房间的最大人数：<input type="number" id="maxNum"> <br><br>
    <button onclick="addToRoom()">进入房间</button>
    <br>
  </div>

<!--  <script type="text/javascript">-->
<!--    export default{-->
<!--      data(){-->
<!--        return {-->
<!--          rules: {-->
<!--          }-->
<!--        }-->
<!--      },-->
<!--      methods: {-->
<!--        addToRoom: function () {-->
<!--          var dto = {-->
<!--            id:$("#id").val(),-->
<!--            fname:$("#name").val(),-->
<!--            roomId:$("#num").val()-->
<!--          }-->
<!--          $.post("/op/addToRoom",dto,function(data){-->
<!--            window.location.href="http://127.0.0.1:5080/openmeetings/hash?secure="+data.message-->
<!--          },"json")-->
<!--        }-->
<!--      }-->
<!--    }-->


<!--  </script>-->
</template>
