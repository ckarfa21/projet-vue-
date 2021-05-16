<template>
    <div class="container">
        <h2>Utilisateurs</h2>
        <table class="table table-bordered">
            <thead>
            <tr>
                <th>Id utilisateur</th>
                <th>Prénom</th>
                <th>Nom</th>
                <th>Email</th>
            </tr>
            </thead>
            <tbody>
              <tr v-for="item in users" :key="item.id">
                  <td>{{ item.id }}</td>
                  <td>{{ item.firstName }}</td>
                  <td>{{ item.lastName }}</td>
                  <td>{{ item.email }}</td>
              </tr>
            </tbody>
        </table>
    </div>
</template>

<script>

    export default {
        name: 'Users',
        props: ['users']
     }
</script>