<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Home</title>
  <link rel="icon" type="image/png" href="astolfopng.png" />
  <link href="new.css" rel="stylesheet" type="text/css" />
  <script src="https://kit.fontawesome.com/8df7d40c3b.js" crossorigin="anonymous"></script>
</head>

<body>
  <nav class="bar">
       <a class="active"><i class="fa fa-fw fa-home"></i> Home </a>
       <a href="about.html"><i class="fa fa-fw fa-info-circle"></i> About </a>
       <a href="games.html"><i class="fa fa-fw fa-gamepad"></i> Games </a>
       <a class="active"><i class="fa fa-fw fa-bookmark"></i> Bookmarklets </a>
       <a href="https://yex-is-very-cool.herokuapp.com/main/discord.gg/d55JGgdW4P"><i class="fab fa-discord"></i> Discord </a>
       <a href="https://chat.undernet.org/#yexsgames"><i class="fa fa-fw fa-wechat"></i> WebChat </a>
       <a href="mailto:152135@mcpsmd.net"><i class="fa fa-fw fa-envelope"></i> Email </a>
  </nav>

  <h1 class="left"> Bookmarklets </h1>
  <p class = "left"> Simply drag and drop these onto your bookmark bar and click them to use them.</p>
  <hr>
  <a class="bmrklet" href="javascript:(function () {var script=document.createElement('script');script.src='https://x-ray-goggles.mouse.org/webxray.js';script.className='webxray';script.setAttribute('data-lang','en-US');script.setAttribute('data-baseuri','https://x-ray-goggles.mouse.org');document.body.appendChild(script);}())"> Inspect </a>
  <a class="bmrklet" href="javascript:(function () {var title=prompt('Enter title name');var icon=prompt('Enter the link of your icon');var link=document.querySelector(&quot;link[rel*='icon']&quot;) || document.createElement('link');link.type='image/x-icon';link.rel='shortcut icon';link.href=icon;document.title=title;document.getElementsByTagName('head')[0].appendChild(link);})();"> Tab Cloak </a>
  <a class = "bmrklet" href="javascript:location='http://translate.google.com/translate?u=%27+++encodeURIComponent(location);&#38;_x_tr_sl=auto&#38;_x_tr_tl=en&#38;_x_tr_hl=en-US"> Google Translate </a>
  <a class="bmrklet" href="javascript:document.body.contentEditable = 'true'; document.designMode='on'; void 0"> Edit Page </a>
  <a class="bmrklet" href="javascript:(function(){var i, nd; function copyChildren(a,b){var i, nn; for(i=0;i<a.childNodes.length;++i) { nn = a.childNodes[i].cloneNode(true); if(nd.importNode) nn = nd.importNode(nn, true); b.appendChild(nn); } } nd=window.open().document; nd.open(); nd.close(); /*140681*/ copyChildren(document.getElementsByTagName('head')[0], nd.getElementsByTagName('head')[0]); copyChildren(document.body, nd.body);})();"> Clone Document </a>
  <a class="bmrklet" href="javascript:q = '' + (window.getSelection ?%20window.getSelection()%20:%20document.getSelection%20?%20document.getSelection()%20:%20document.selection.createRange().text);%20if%20(!q)%20q%20=%20prompt(%22You%20didn%27t%20select%20any%20text.%20%20Enter%20a%20search%20phrase:%22,%20%22%22);%20if%20(q!=null)%20location=%22http://www.google.com/search?q=%22%20+%20escape(q).replace(/%20/g,%20%22+%22);%20void%200"> Google Search </a>
  
</body>
</html>
