<template>
<div>
 <p>{{message}}</p>
 <p>{{username}}</p>
</div>
</template>

<script>
export default {
  name: 'BaseHeader',
  data (){
      return{
          message: 'Home',
          username: 'GOGBE MOUSSA'
        }
  }
}