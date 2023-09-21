<template>
    <div>
    <table border="1">
        <tr>
            <th>Name:</th>
            <th>Age:</th>
            <th>School:</th>
            <th>Hobby:</th>
            <th>Action:</th>

        </tr>
        <tr>
            <td>{{ user.name }}</td>
            <td>{{ user.age }}</td>
            <td>{{ user.school }}</td>
            <td>{{ hobby }}</td>
<td><a href="">Edit</a></td>
<td><a href="">Delete</a></td>

        </tr>
   
    </table>
  </div>
  </template>
  
  <script>
  export default {
    name: 'ViewUser',
    props: {
      user: Object,
      hobby: String,
    },
  };
  </script>
  
  <style scoped>
  </style>
  