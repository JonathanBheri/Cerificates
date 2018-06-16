
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
    background-color: #777;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
}

.active, .collapsible:hover {
    background-color: #555;
}
.collapsible:after {
    content: '\002B';
    color: white;
    font-weight: bold;
    float: right;
    margin-left: 5px;
}

.active:after {
    content: "\2212";
}

.content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    background-color: #f1f1f1;
}
</style>
</head>
<body>

<h2>Certificates</h2>



<p>LinkedIn Learning:</p>
<button class="collapsible">Certificate of Industrial Automation </button>
<div class="content">
<embed src="https://drive.google.com/viewerng/viewer?embedded=true&url=https://github.com/JonathanBheri/Certificate/raw/master/CertificateOfCompletion_Learn%20Industrial%20Automation.pdf" width="800" height="625" align="center">
    <br>
</div>
<button class="collapsible">Certificate of OpenCV 3 in Python </button>
<div class="content">
<embed src="https://drive.google.com/viewerng/viewer?embedded=true&url=https://github.com/JonathanBheri/Certificate/raw/master/CertificateOfCompletion_Opencv%20For%20Python%20Developers.pdf" width="800" height="625" align="center">
    <br>
</div>
<button class="collapsible">Certificate of Raspberry Pi</button>
<div class="content">
<embed src="https://drive.google.com/viewerng/viewer?embedded=true&url=https://github.com/JonathanBheri/Certificate/raw/master/CertificateOfCompletion_Raspberry%20Pi%20Essential%20Training.pdf" width="800" height="625" align="center">
    <br>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
        this.classList.toggle("active");
        var content = this.nextElementSibling;
        if (content.style.display === "block") {
            content.style.display = "none";
        } else {
            content.style.display = "block";
        }
    });
}
</script>

</body>
