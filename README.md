<!doctype.html>
<html>
<head>
<title>let's do it</title>
</head>
<body>
hi....this is a sample website created by me for my learnings.you can know about me on facebook by visiting


<a href=https://www.facebook.com/profile.php?id=100095258707627&mibextid=JRoKGi>my profile</a>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Insertion</title>
</head>

   <image> <img src="Device storage/Pictures/Screenshots/ Screenshot_2024-04-18-12-50-04-38_998d 3425f9e75a0428f0fabdce419960.jpg" alt="That's me"></image><hr>
   <marquee behavior="scroll" direction="left">
welcome to my website</marquee>

<h1><div align="center"><p style="background-color:green;">Let's know about the historical interests of naogaon city</p></marquee></p></div></h1>
<b>There is a list of the historical interests where you can visit with your family or friends or alone.</b>
<br><i>(note: you can know more by clicking on the name of the historical place you want to know)</br></i>
<ul>
<li>no 1: <a href=https://en.m.wikipedia.org/wiki/Kusumba_Mosque>kusumba</a>
<br><h2>কুসুম্বা মসজিদ</h2>
    <img src="https://en.m.wikipedia.org/wiki/File:Kusumba_Mosque,_Naogaon.jpg" alt="কুসুম্বা"></br>
<li>no 2: <a href=https://en.m.wikipedia.org/wiki/Somapura_Mahavihara>Sompur mohavihara</a>
<br><h2>সোমপুর মহাবিহার</h2>
    <img src="https://en.m.wikipedia.org/wiki/File:Paharpur_Buddhist_Bihar.jpg" alt="মহাবিহার"></br>
<li>no 3: <a href=https://bn.m.wikipedia.org/wiki/%E0%A6%A6%E0%A7%81%E0%A6%AC%E0%A6%B2%E0%A6%B9%E0%A6%BE%E0%A6%9F%E0%A6%BF_%E0%A6%B0%E0%A6%BE%E0%A6%9C%E0%A6%AC%E0%A6%BE%E0%A6%A1%E0%A6%BC%E0%A7%80>Dubolhati rajbari</a>
  <br><h2>দুবলহাটি রাজবাড়ি</h2>
    <img src="https://bn.m.wikipedia.org/wiki/%E0%A6%9A%E0%A6%BF%E0%A6%A4%E0%A7%8D%E0%A6%B0:%E0%A6%A6%E0%A7%81%E0%A6%AC%E0%A6%B2%E0%A6%B9%E0%A6%BE%E0%A6%9F%E0%A6%BF_%E0%A6%B0%E0%A6%BE%E0%A6%9C%E0%A6%AC%E0%A6%BE%E0%A6%A1%E0%A6%BC%E0%A7%80.jpg" alt="Dubolhati rajbari"> </br>
<li>no 4: <a href=https://naogaon.site/patisar-rabindra-kachari-bari-atrai-naogaon/>Patisar Rabinda Kachari Bari</a>
 <br><h2>পতিশর কুঠিবাড়ি</h2>
    <img src="https://bn.m.wikipedia.org/wiki/%E0%A6%9A%E0%A6%BF%E0%A6%A4%E0%A7%8D%E0%A6%B0:%E0%A6%AA%E0%A6%A4%E0%A6%BF%E0%A6%B8%E0%A6%B0_%E0%A6%B0%E0%A6%AC%E0%A7%80%E0%A6%A8%E0%A7%8D%E0%A6%A6%E0%A7%8D%E0%A6%B0_%E0%A6%95%E0%A6%BE%E0%A6%9A%E0%A6%BE%E0%A6%B0%E0%A7%80_%E0%A6%AC%E0%A6%BE%E0%A6%A1%E0%A6%BC%E0%A6%BF%E0%A6%B0_%E0%A6%AE%E0%A7%82%E0%A6%B2_%E0%A6%AB%E0%A6%9F%E0%A6%95.jpg" alt="পতিশর"></br>
<li>no 5: <a href=https://en.m.wikipedia.org/wiki/Dibar_Dighi>Dibar dighi</a>
<br><h2>দিবর দিঘী</h2>
    <img src="https://en-m-wikipedia-org.translate.goog/wiki/File:A_View_of_Dibor_Dighi.jpg?_x_tr_sl=en&_x_tr_tl=bn&_x_tr_hl=bn&_x_tr_pto=tc" alt="দিবর দিঘী"></br>
<li>no 6: <a href=https://bn.m.wikipedia.org/wiki/%E0%A6%86%E0%A6%B2%E0%A6%A4%E0%A6%BE%E0%A6%A6%E0%A7%80%E0%A6%98%E0%A6%BF_%E0%A6%9C%E0%A6%BE%E0%A6%A4%E0%A7%80%E0%A6%AF%E0%A6%BC_%E0%A6%89%E0%A6%A6%E0%A7%8D%E0%A6%AF%E0%A6%BE%E0%A6%A8>Alta dighi</a>
<br><h2>আলতা দিঘী</h2>
    <img src="https://bn.m.wikipedia.org/wiki/%E0%A6%9A%E0%A6%BF%E0%A6%A4%E0%A7%8D%E0%A6%B0:Dense_Forest_-_Alta_Dighi_National_Park.jpg" alt="আলতা দিঘী"></br>
<p>These are the main places of interest in Naogaon,Rajshahi,Bangladesh.</p>
<h2>Comment section</h2>
    <div id="comments">
        <!-- Existing comments will be displayed here -->
    </div>
    <h3>Remember to leave a nice comment here for my page</h3>
    <form id="commentForm">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br>
        <label for="comment">Comment:</label><br>
        <textarea id="comment" name="comment" rows="4" cols="50"></textarea><br>
        <button type="submit">Submit</button>
    </form>

    <script>
        document.getElementById('commentForm').addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent the default form submission
            // Get input values
            var name = document.getElementById('name').value;
            var comment = document.getElementById('comment').value;
            // Create a new comment element
            var commentElement = document.createElement('div');
            commentElement.className = 'comment';
            commentElement.innerHTML = '<strong>' + name + ':</strong> ' + comment;
            // Append the new comment to the comments section
            document.getElementById('comments').appendChild(commentElement);
            // Clear the form fields
            document.getElementById('name').value = '';
            document.getElementById('comment').value = '';
        });
    </script>
    <div align="center"><p style="background-color:white;">Powered by:<a href=https://www.facebook.com/profile.php?id=100095258707627&mibextid=JRoKGi>Md Mahmid Hossain</a></p></marquee></p></div>
</body>
</html.
