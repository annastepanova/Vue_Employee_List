<template>
  <div id="app" class="small-container">
    <h1>Employees</h1>

    <employee-form />
    <employee-table :employees="employees" />
  </div>
</template>

<script>
  import EmployeeTable from '@/components/EmployeeTable.vue'
  import EmployeeForm from '@/components/EmployeeForm.vue'

  export default {
    name: 'app',
    components: {
      EmployeeTable,
      EmployeeForm
    },
    data() {
      return {
        employees: [
          {
            id: 1,
            name: 'Harry Potter',
            email: 'potter@hogwards.com',
          },
          {
            id: 2,
            name: 'Hermione Granger',
            email: 'granger@hogwards.com',
          },
          {
            id: 3,
            name: 'Ron Weasley',
            email: 'weasley@hogwards.com',
          },
        ],
      }
    },
  }
</script>

<style>
  button {
    background: #009435;
    border: 1px solid #009435;
  }

  .small-container {
    max-width: 680px;
  }
</style>
