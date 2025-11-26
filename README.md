<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>FAQ Page</title>
<style>
body {
margin: 0;
font-family: Arial, sans-serif;
background-color: #f8f8f8;
}


/* Header */
.header {
background-color: #8ed18e;
padding: 20px 40px;
display: flex;
justify-content: space-between;
align-items: center;
font-size: 24px;
font-weight: bold;
}


.header .username {
font-size: 20px;
font-weight: normal;
}


/* Main Content */
.container {
display: flex;
justify-content: space-between;
padding: 40px;
}


.left-section {
width: 50%;
}


.left-section h1 {
font-size: 48px;
margin-bottom: 20px;
}


.search-box {
width: 80%;
padding: 15px;
font-size: 18px;
border-radius: 50px;
border: 1px solid #ccc;
margin-bottom: 30px;
}


.faq-item {
font-size: 26px;
margin: 20px 0;
cursor: pointer;
}


.faq-item span {
float: right;
font-weight: bold;
}


/* Right Section */
.right-section {
width: 40%;
display: flex;
justify-content: center;
align-items: center;
}


.faq-graphic {
font-size: 180px;
font-weight: bold;
color: #8ed18e;
}
</style>
</head>
<body>
<div class="header">
<div>Short IN</div>
<div class="username">Hello, username</div>
</div>


<div class="container">
<div class="left-section">
<h1>Frequently Asked<br />Questions</h1>


<input type="text" class="search-box" placeholder="Search questions" />


<div class="faq-item">About our profile? <span>+</span></div>
<div class="faq-item">News and topics? <span>+</span></div>
</html>
