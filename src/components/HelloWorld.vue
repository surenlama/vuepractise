<template>
  <div >
    <h1>{{ title }}</h1>
    <ViewUser
     :user="user" 
    :hobby="hobby">
    </ViewUser>
  </div>
</template>

<script>
import ViewUser from './ViewUser.vue';
export default {
  name: 'HelloWorld',
  components: {
    ViewUser,
  },
  data(){
        return {
            title: 'Welcome to School managment System',
            user: {
                'name':'Hari',
                'age': 24,
                'school': 'Adwitiya Boarding School'
            },
            hobby: 'football'
        }
    },
}


</script>

<style scoped>
</style>
