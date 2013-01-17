streaminTV
==========
This is a web application for streaming TV

To open the application open the tv.html file.

The chanels are configed in the js/tv.js file
in the next format:
{name:"2",
  urls:['<script type="text/javascript" src="http://veemi.com/javascript/embedPlayer.js"></script>',
	'<object height="500px" width="1000px" type="application/x-shockwave-flash" data="http://www.justin.tv/widgets/live_embed_player.swf?channel=kimberly6575" id="live_embed_player_flash"  bgcolor="#000000"><param name="allowFullScreen" value="true"/><param name="allowScriptAccess" value="always" /><param name="allowNetworking" value="all" /><param name="movie" value="http://www.justin.tv/widgets/live_embed_player.swf" /><param name="flashvars" value="hostname=www.justin.tv&channel=kimberly6575&auto_play=false&start_volume=25" /></object><a href="http://www.justin.tv/kimberly6575#r=-rid-&amp;s=em" class="trk" style="padding:2px 0px 4px; display:block; width:345px; font-weight:normal; font-size:10px; text-decoration:underline; text-align:center"/>',
	'<object height="500px" width="1000px" type="application/x-shockwave-flash" id="dashboard" name="dashboard" data="http://rcs.mako.co.il/flash_swf/players/makoPlayer/VideoPlayer.swf?ver=1" style="visibility: visible;"><param name="allowScriptAccess" value="always"><param name="allowfullscreen" value="true"><param name="wmode" value="window"><param name="flashvars" value="domain=http://www.mako.co.il&amp;vcmid=4191ce1645bc0310VgnVCM2000002a0c10acRCRD&amp;videoChannelId=0b0fad1cfce17210VgnVCM100000290c10acRCRD&amp;galleryChannelId=0b0fad1cfce17210VgnVCM100000290c10acRCRD&amp;skin=makoLiveSkin.swf&amp;autoplay=true&amp;showSuggest=true&amp;suggestMore=16&amp;showlogo=-1&amp;suggestMoreType=1&amp;leaveOldSuggest=true&amp;md=false&amp;bigSuggestPlayerWidth=900"></object>'
	]}

the attribute "name" states the name that will be displayed in the application
the urls states the sources of the chanells.

