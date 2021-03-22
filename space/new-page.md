---
title: Planets
description: 
published: false
date: 2021-03-22T11:54:22.556Z
tags: 
editor: markdown
dateCreated: 2021-03-22T11:54:22.556Z
---

# Planets
---
<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for planet...">

<table id="myTable">
  <tr>
    <th> Planet </th>
    <th> System </th>
    <th> Purpose </th>
    <th> Atmosphere </th>
  </tr>
  <tr>
    <td> Aecor </td>
    <td> Cordis </td>
    <td> Colonization, Mining </td>
    <td> Habitable </td>
  </tr>
  <tr>
    <td> Arbusto </td>
    <td> Antares </td>
    <td> Farming </td>
    <td> Habitable </td>
  </tr>
  <tr>
    <td> Cerus Alpha </td>
    <td> Malium </td>
    <td> Mining </td>
    <td> Hot </td>
  </tr>
  <tr>
    <td> Cerus Beta </td>
    <td> Bellum </td>
    <td> Colonization </td>
    <td> No Atmosphere </td>
  </tr>
      
<style>
  
{box-sizing: border-box;}
  
#myInput {
  background-image: url('https://imgur.com/ImYrc1t.png');
  background-position: -0px -0px;
  background-repeat: no-repeat;
  background-size: 50px 50px;
  width: 25%;
  font-size: 16px;
  padding: 12px 20px 12px 50px;
  border: 1px solid #ddd;
  margin-bottom: 12px;}
  
#myTable {
  border-collapse: collapse;
  
  border: 1px solid #ddd;
  font-size: 18px;}
</style>

<script>
function myFunction() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[1];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
</script>