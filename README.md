<!DOCTYPE html>
 <html lang="en">
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Student Grades Table</title>
     <style>
         body {
             font-family: Arial, sans-serif;
             background-color: #f4f4f4;
             margin: 0;
             padding: 20px;
         }
         table {
             width: 80%; /* Adjust as needed */
             border-collapse: collapse;
             margin: 20px auto; /* Center the table */
             box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
             background-color: white;
         }
         th, td {
             padding: 12px 15px;
             text-align: left;
             border-bottom: 1px solid #ddd;
         }
         th {
             background-color: #343a40; /* Dark header */
             color: white;
             text-transform: uppercase;
         }
         tbody tr:hover {
             background-color: #f5f5f5;
         }
         /* Conditional formatting for grades */
         .pass {
             color: green;
         }
         .fail {
             color: red;
         }
     </style>
 </head>
 <body>
     <h2>Student Grades</h2>
     <table>
         <thead>
             <tr>
                 <th>Student ID</th>
                 <th>Name</th>
                 <th>Subject</th>
                 <th>Grade</th>
             </tr>
         </thead>
         <tbody>
             <tr>
                 <td>101</td>
                 <td>Roland Balla</td>
                 <td>Math</td>
                 <td class="pass">92</td>
             </tr>
             <tr>
                 <td>102</td>
                 <td>Regina Llandelar</td>
                 <td>Math</td>
                 <td class="fail">72</td>
             </tr>
             <tr>
                 <td>101</td>
                 <td>Adrian Baloloy</td>
                 <td>Science</td>
                 <td class="pass">88</td>
             </tr>
             <tr>
                 <td>102</td>
                 <td>Leandro Espayos</td>
                 <td>Science</td>
                 <td class="pass">75</td>
             </tr>
             <tr>
                 <td>103</td>
                 <td>Jodelle Blanqueza</td>
                 <td>Math</td>
                 <td class="pass">85</td>
             </tr>
             <tr>
                 <td>103</td>
                 <td>Louie Bustamante</td>
                 <td>Science</td>
                 <td class="fail">73</td>
             </tr>
         </tbody>
     </table>
 </body>
 </html>
