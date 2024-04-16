<template>
  <div class="tran">
    <div class="left">dsad</div>
    <div class="right">
      <div>
        <el-table
          :data="tableData"
          style="width: 100%"
          :show-overflow-tooltip="{
            placement: 'bottom',
          }"
          tooltip-effect="light"
          row-key="id"
        >
          <el-table-column prop="date" label="Date" width="100" />
          <el-table-column prop="name" label="Name" width="200" />
        </el-table>
      </div>
    </div>
  </div>
</template>
干坞
<style>
.tran {
  display: grid;
  grid-template-columns: 100px 1fr;
  height: 400px;
}
.right {
  transform-origin: left top;
  transform: scale(1.6);
}
</style>
<script lang="ts" setup>
const tableData = [
  {
    date: "N",
    name: "No2323",
    address: "No. ",
  },
  {
    date:
      "No. 189xLos AngelesNo. 189, Grove St, Los AngelesNo. 189, Grove St, Los AngelesNo. 189, Grove St, Los AngelesNo. 189, Grove St, Los Angeles",
    name:
      "No. 189, Grove St, Los Angeles No. 189, Grove St, Los AngelesNo. 189, Grove St, Los AngelesNo. 189, Grove St, Los AngelesNo. 189, Grove St, Los AngelesNo. 189, Grove St, Los AngelesNo. 189, Grove St, Los Angeles",
    address:
      "No. 189, Grove St, Los Angeles No. 189, Grove St, Los AngelesNo. lesNo. 189, Grove St, Los AngelesNo. 189, Grove St, Los Angeles",
  },
];
</script>
