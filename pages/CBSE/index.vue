<template>
  <div>
    <Navbar />

    <b-table striped hover :items="items" :fields="fields">
      <template v-slot:cell(test)="data">
        <span v-html="data.value"></span>
      </template>
    </b-table>
  </div>
</template>

<script>
export default {
  data() {
    return {
      // Note `isActive` is left out and will not appear in the rendered table
      fields: ["Subject", "Description", "Question", "test"],
      items: [
        {
          isActive: true,
          Question: 40,
          Subject: "Math",
          Description: "Trigno,Clac,etc..",
          test: "<a href='/Instruction'>Start</a>",
        },
        {
          isActive: false,
          Question: 21,
          Subject: "Science",
          Description: "Chem,Physics",
          test: "start",
        },
      ],
    };
  },
};
</script>