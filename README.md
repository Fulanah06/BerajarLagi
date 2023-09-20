# Website Tabel
HTML
--
<!DOCTYPE html>
<html lang="en">
<head>
  <title>SOAL QUIZ A TEKNOLOGI INFORMASI</title>
  <link rel="stylesheet" href="css/style.css">
</head>

<body style="background-color: #f0ead2;">

<table>

  <tr>
    <td> <img src="img/logo.png" height="200" width="200">  </td>
    <td><h2  style="text-align:center; margin-left: 230px;" >WELCOME TO BUMIGORA UNIVERSITY
    </h2></td>
 
</table>

  <div class="flexbox">
    <div style="background-color: #dde5b6;">
      <div class="tautan">

        <ul>
          <h2> MAIN MENU </h2>
            <li><a href="#">Buku LKS</a></li>
            <li> <a href="#HOME">Beranda</a> </li>
            <li> <a href="#ABOUT US">Tentang Kami</a></li>
            <li> <a href="#HOME">Siti Nurhalima</a></li>
            <li> <a href="#HOME">2101020035<ali>
        </ul>
        
      </div>
    </div>  

       <br>
      
    <div>
      <h2 style="text-align: center;"> Halaman Mahasiswa Bermasalah: </h2>
      <table>
        <tr style="background-color: #dde5b6;">
          <td style="width: 60px;"> NO </td>
          <td style="width: 200px;"> NAMA </td>
          <td style="width: 150px;"> NIM </td>
          <td style="width: 150px;"> KELAS </td>
          <td style="width: 150px;"> FOTO </td>
          <td style="width: 150px;"> NO TELPON </td>
        </tr>

       <tr style="background-color: #dde5b6;">
          <td> 1 </td>
          <td> TOMI TRI SUJAKA </td>
          <td> 12.11.5955 </td>
          <td> 12-S1-TI-04 </td>
          
          <td> <img src="img/2022.JPG" height="110" width="120"> </td>
          <td> 08888888888 </td>
        </tr>
        <tr style="background-color: white;">
          <td> 1 </td>
          <td> RIZKI EKA PRASOEDJO </td>
          <td> 12.11.5955 </td>
          <td> 12-S1-TI-04 </td>
          
          <td> <img src="img/rizkee.jpg" height="110" width="120"> </td>
          <td> 08888888888 </td>
        </tr>

      <tr style="background-color: #dde5b6;" >
        <td>2</td>
        <td>ILHAM MUBAROK</td>
        <td>12.11.5983</td>
        <td>12-S1-TI-04</td>
        <td> <img src="img/eelham.jpg" height="110" width="120"> </td>
        <td> 08666666666 </td>
      </tr>

        <tr style="background-color: white;">
            <td> 3 </td>
            <TD>ANDI AGUS SALIM</TD>
            <td>12.11.6007</td>
            <td>12-S1-TI-04 </td>
            <td> <img src="img/andee.jpg" height="110" width="120"> </td>
          <td> 084444d </td>
        </tr>
         </div>
  </div>
    </table>
  <div class="footer">
    Siti Nurhalima(2101020035)
  </div>
</body>
</html>

CSS
--
@import url('https://fonts.googleapis.com/css2?family=Kanit&display=swap');

html {
    max-width: 100%;
    font-family: 'Kanit', sans-serif;
}

body {
    magin: 0;
    color: #6c584c;
   
}

li,a, h2 {
    text-decoration: none;
    color: #6c584c;
}

table, td, td {
    border:#f0ead2 solid 3px ;
    text-align: center;
}

.navbar {

    background-color: #893168;
    overflow: hidden;
}

.tautan a:hover {
    text-decoration: underline;
}

.flexbox {
    align-items: stretch;
    justify-content: left;
    display: flex;
    flex-direction: row;
    background-color: #f0ead2;
}

.flexbox > div {
    padding: 15px;
    margin: 15px;
    text-align: justify;
    background-color: #f0ead2;
}

.footer {
    position: relative;
    background-color: #adc178;
    clear: both;
    padding: 1%;
    margin-top: -0%;
    color: #6c584c;
    text-align: center;
}




