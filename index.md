<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1,user-scalable=0"/> 
<style>
body {font-family: Arial, Helvetica, sans-serif;
overflow: scroll;

}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 10px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: scroll; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
}

/* Modal Content */
.modal-content {
  background-color: grey;
  margin: auto;
  /* padding: 10px; */
  border: 1px solid #888;
  width: 30%;
}

/* The Close Button */
.close {
  color: #aaaaaa;
  float: right;
  font-size: 28px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
}
.frame {
  height: 700px;
  width: 100%;
}

@media only screen and (max-width: 600px) {
  .modal-content {
    width: 95%;
  }
}

</style>
</head>
<body>

<h2>Modal Example</h2>

<!-- Trigger/Open The Modal -->
<button id="myBtn">Open Modal</button>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>
<h2>Modal Example</h2>

<!-- The Modal -->
<div id="myModal" class="modal">

  <!-- Modal content -->
  <div class="modal-content">
    <span class="close">&times;</span>
   
    <iframe class="frame" src="https://frms-sit-1647.paymentus.io/xotp/pm/frms?authToken=61166C5C318F1520897AD6814065D6D6B94314B96CF9FAF9E11E69B3EEF36CE2AAC4A853B811ECA832EAAFDE23D3EB703967E68375653056275203B9B0D7CD6028D83CF7E905A8D32B4524BBD121CBEF5487CCCA1BB8B0E635BB2C6975866A16A7B0420D47FB248F2FF26084D0E7D1147A8B329336087C69D434A2188553E47B1170484409B90B1902B4732F09E54FBAA053D6BE90308722F60137D012905A75BA813082146CDF24B90504526A1FE4A8DE2DF19995ECC16AE9FC10EBDF11F320CE98D0B54F0955C30324A00410C87E853097EF9FD3FE0E1FD5C60316A82DD7273497349C22B965BBC25A45EB5464D2992EAA9C82A03C9661B562569E425B50A7F7FB14C21F6F35AF54B5F0F7AD593E1D30A2D99C2F77D90EF8FABC84CC457611&iframe=true" frameborder="0"></iframe>
      
  </div>

</div>

<script>
// Get the modal
var modal = document.getElementById("myModal");

// Get the button that opens the modal
var btn = document.getElementById("myBtn");

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks the button, open the modal 
btn.onclick = function() {
  modal.style.display = "block";
  document.getElementsByTagName("body")[0].style.overflow = "hidden";
}

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  modal.style.display = "none";
  document.getElementsByTagName("body")[0].style.overflow = "scroll";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>

</body>
</html>

