<template>
  <div id="employee-table">
    <table>
      <thead>
        <tr>
          <th>Employee name</th>
          <th>Employee email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Harry Potter</td>
          <td>potter@hogwards.com</td>
        </tr>
        <tr>
          <td>Hermione Granger</td>
          <td>granger@hogwards.com</td>
        </tr>
        <tr>
          <td>Ron Weasley</td>
          <td>weasley@hogwards.com</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
  export default {
    name: 'employee-table',
  }
</script>

<style scoped></style>
