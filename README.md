## Hi there 👋
### am KigoryGH
![GitHub Mini Badge](https://ghstats.dev/api/mini?username=KigoryGH)  ![GitHub Mini Badge](https://ghstats.dev/api/mini?username=KigoryGH&metric=commits)  ![GitHub Mini Badge](https://ghstats.dev/api/mini?username=KigoryGH&metric=issues)  ![GitHub Mini Badge](https://ghstats.dev/api/mini?username=KigoryGH&metric=hours)  ![GitHub Mini Badge](https://ghstats.dev/api/mini?username=KigoryGH&metric=streak)  ![GitHub Mini Badge](https://ghstats.dev/api/mini?username=KigoryGH&metric=streak)  ![GitHub Mini Badge](https://ghstats.dev/api/mini?username=KigoryGH&metric=contributions&label=Contributions)

![Contribution Sparkline](https://ghstats.dev/api/sparkline?username=KigoryGH&days=30&width=320&height=80&hide_border=true)

![GitHub Stats Card](https://ghstats.dev/api/card?username=KigoryGH&show_ring=false&hide_title=true) <img src="https://ghchart.rshah.org/8a2be2/KigoryGH" width="2000" alt="GitHub Contribution Grid" />

![Top Languages](https://ghstats.dev/api/langs?username=KigoryGH&theme=dracula&hide_border=true&hide_title=true&max_langs=12)


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Debian:stable Banner</title>
<style>
  body {
    background: #0d1117;
    margin: 0;
    padding: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
  pre {
    font-family: "Courier New", monospace;
    font-size: 14px;
    line-height: 1.1;
    white-space: pre;
    margin: 0;
  }
  .char {
    display: inline-block;
  }
</style>
</head>
<body>
<pre id="art">mmm          #        "                                  m           #      ""#          
 #   "m  mmm   #mmm   mmm     mmm   m mm           mmm   mm#mm   mmm   #mmm     #     mmm  
 #    # #"  #  #" "#    #    "   #  #"  #    #    #   "    #    "   #  #" "#    #    #"  # 
 #    # #""""  #   #    #    m"""#  #   #          """m    #    m"""#  #   #    #    #"""" 
 #mmm"  "#mm"  ##m#"  mm#mm  "mm"#  #   #    #    "mmm"    "mm  "mm"#  ##m#"    "mm  "#mm"</pre>

<script>
  // Recreate a lolcat-style diagonal rainbow gradient
  const pre = document.getElementById('art');
  const lines = pre.textContent.split('\n');
  pre.innerHTML = '';

  const freq = 0.1; // controls how fast colors cycle

  lines.forEach((line, rowIndex) => {
    const lineDiv = document.createElement('div');
    [...line].forEach((ch, colIndex) => {
      const span = document.createElement('span');
      span.className = 'char';
      span.textContent = ch === ' ' ? '\u00A0' : ch;

      const hue = ((rowIndex * 6) + (colIndex * 4)) % 360;
      span.style.color = `hsl(${hue}, 100%, 65%)`;

      lineDiv.appendChild(span);
    });
    pre.appendChild(lineDiv);
  });
</script>
</body>
</html>
