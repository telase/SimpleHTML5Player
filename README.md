# SimpleHTML5Player

<!DOCTYPE html>
<html>
<head>
<meta charset=utf-8 />
<title>TeLaSe Live</title>
  
<meta name="viewport" content="width=device-width, initial-scale=1">
 <link rel="stylesheet" href="./dist/plyr.css">
  
<script src="./dist/hls.js"></script>
  <script src="./dist/plyr.min.js"></script>
  <script src="./dist/script.js"></script>

  <div class="container">
  
    <video controls crossorigin playsinline >
      <source 
        type="application/x-mpegURL"       
		src="https://tv-trtspor1.live.trt.com.tr/master.m3u8">
    </video>
  </div>
  
</body>
</html>
