<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Ordered list</title>
</head>
<body>
   <h2>HTML LIST</h2> 
   <h3>Ordered List</h3>
   <ol type="i"start="1">
    <li>Blaise Kimiti</li>
    <li>Jotham Ikere</li>
    <li>Mercy Chemutai</li>
    <li>Rebeckah Nyambura</li>
    <li>Stacy Nekesa</li>
   </ol>

   <h3>HTML IMAGES</h3>
   <img src="https://images.pexels.com/photos/2131720/pexels-photo-2131720.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"  height="200" width="200">

   <h3>HTML TABLES</h3>
   <caption>Contact Details</caption>
   <br><br>

   <table table border="1">
    <tr>
        <th>Name</th>
        <th>Address</th>
        <th>Mobile</th>
        <th>Emails</th>
    </tr>
    
    <tr>
      <td>Blaise Kimiti</td>  
      <td>PO. BOX 30 KARATINA</td>
      <td>0115915230</td>
      <td>kimitiblaise@gmail.com</td>
    </tr>

    <tr>
        <td>Jotham Ikere</td>
        <td>PO. BOX 110 KIAMBU</td>
        <td>0720657479</td>
        <td>ikerejotham@gmail.com</td>
    </tr>

    <tr>
        <td>Mercy Chemutai</td>
        <td>PO. BOX 120 NAIROBI</td>
        <td>0712824897</td>
        <td>mtonui435@gmail.com</td>
    </tr>
    
    <tr>
        <td>Rebeckah Nyambura</td>
        <td>PO. BOX 130 ELDORET</td>
        <td>0715912225</td>
        <td>shikukubecky@gmail.com</td>
    </tr>

    <tr>
        <td>Stacy Nekesa</td>
        <td>PO. BOX 140 NAIROBI</td>
        <td>0798645949</td>
        <td>murambinekesa@gmail.com</td>
    </tr>

   </table>

   <h3>Please fill in this form</h3>
   <form action="" method="">
    <label for="full_name">Full Nmaes:</label>
    <br>
    <input type="text" id="full_name" name="full_name" placeholder="Enter your full name here">
    <br><br>
    <label for="Gender">Gender</label>
    <br>
    <input type="radio" name="Gender" value="Male">Male
    <br>
    <input type="radio" name="Gender" value="Female">Female
    <br><br>
    <label for="Languages">Languages</label>
    <br><br>
    <input type="checkbox" name="Languages" value="English">English
    <input type="checkbox" name="Languages" value="Kiswahili">Kiswahili
    <input type="checkbox" name="Languages" value="French">French
    <input type="checkbox" name="Languages" value="German">German
    <input type="checkbox" name="Languages" value="Afrikaans">Afrikaans

    <br><br>

    <label for="Country">Choose your country of residence:</label>

    <select name="Country"></option>
    <br>
    <option value="Kenya">Kenya</option>
    <option value="Sudan">Sudan</option>
    <option value="Ghana">Ghana</option>
    <option value="Ivory Coast">Ivory Coast</option>
    <option value="Malawi">Malawi</option>
    <option value="South Africa">South Africa</option>

    <br><br>

    <input type="Submit" value="Register"><br>
    <br>
    <button type="Reset">Cancel</button>
    <br>
    



   </form>
   

</body>



