<h1>
  <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/d3359cb00ab0b5ed8f2e1fe3fceb4fbaf3b614340f8c0db99c17b9f50b351770/68747470733a2f2f656d6f6a69732e736c61636b6d6f6a69732e636f6d2f656d6f6a69732f696d616765732f313533313834393433302f343234362f626c6f622d73756e676c61737365732e6769663f31353331383439343330"><img src="https://camo.githubusercontent.com/d3359cb00ab0b5ed8f2e1fe3fceb4fbaf3b614340f8c0db99c17b9f50b351770/68747470733a2f2f656d6f6a69732e736c61636b6d6f6a69732e636f6d2f656d6f6a69732f696d616765732f313533313834393433302f343234362f626c6f622d73756e676c61737365732e6769663f31353331383439343330" width="30" data-canonical-src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" style="max-width: 100%;"></a>Hey! Nice to see you.</h1>
<p>Welcome to my profile!</p>
I'm <b>MD. Mynul Islam Soiket</b>, <p>Fullstack developer from <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/02ec7bff8316cdb0109565a5a30250ee2098b5cb8e0ce93dadc557d8d13d35b5/68747470733a2f2f696d6167652e666c617469636f6e2e636f6d2f69636f6e732f706e672f3531322f3332332f3332333239392e706e67"><img src="https://camo.githubusercontent.com/02ec7bff8316cdb0109565a5a30250ee2098b5cb8e0ce93dadc557d8d13d35b5/68747470733a2f2f696d6167652e666c617469636f6e2e636f6d2f69636f6e732f706e672f3531322f3332332f3332333239392e706e67" width="13" data-canonical-src="https://image.flaticon.com/icons/png/512/323/323299.png" style="max-width: 100%;"></a><b> Dhaka, Bangladesh.</b></p><br><br>

- 🔭 I’m currently working at <b>YetFix Limited</b> as a Web Developer.
- 💞️ I’m looking to collaborate on Laravel based projects & IT Operations on any organizations. 
- 📫 How to reach me: misoiket@gmail.com

<?php /*
Name: Social Media Icons Template Part 
Description: Add Facebook, Twitter, Google+ and LinkedIn sharing to your template files with this easy to adapt tempate-part
Author: Piet Bos
Author URI: http://wpti.ps
Instructions: Step 1. Take the code from line 10-36 of this file, paste them into a blank file, save that file as icons-social.php and upload it to your theme's directory. On lines 19 and 21 you need to fill in your Twitter username and on line 24 you need to upload your favourite tweet-button (or grab it from http://a2.twimg.com/a/1319826270/images/goodies/tweetn.png) to the images folder of your theme. Step 2. Take line 39 of this file and paste it into your template files on the place where you want the icons to show up. Step 3. Take the scripts of line 42-49 and paste them in your footer.php file just above the closing </body> tag. Step 4. Style through CSS. NOTE that with the code below you will get 4 working share buttons. If you however want to make adjustments then visit the following pages: Facebook (http://developers.facebook.com/docs/reference/plugins/like/), Twitter (https://dev.twitter.com/docs/tweet-button), Google+ (http://www.google.com/webmasters/+1/button/), LinkedIn (https://developer.linkedin.com/plugins/share-button).
Version: 1.0
License: GPLv2
*/ ?>
<?php // START Social Media Icons Template Part ?>
<div class="social_media_icons">
	<ul>
		<li class="item facebook">
			<iframe src="http://www.facebook.com/plugins/like.php?href=<?php the_permalink() ?>&amp;layout=button_count&amp;show_faces=true&amp;width=40&amp;action=like&amp;font=verdana&amp;colorscheme=light&amp;height=" scrolling="no" frameborder="0" style="border:none; overflow:hidden; width:100px; height:21px;" allowTransparency="true"></iframe>
		</li><!-- .facebook -->
		<li class="item twitter">
			<a href="https://twitter.com/share" class="twitter-share-button"
			      data-url="<?php the_permalink() ?>"
			      data-via="twitter-username"
			      data-text="<?php the_title(); ?>"
			      data-related="twitter-username"
			      data-count="horizontal">
					<?php // add a Twitter image to your themes images folder and call it with the line below ?>
					<img src="<?php bloginfo('stylesheet_directory'); ?>/images/tweet.png" alt="tweetbutton" /> 
				</a>
		</li><!-- .twitter -->
		<li class="item gplus">
			<g:plusone size="medium"></g:plusone>
		</li><!-- .gplus -->
		<li class="item linkedin">
			<script src="http://platform.linkedin.com/in.js" type="text/javascript"></script>
			<script type="IN/Share" data-counter="right"></script>
		</li><!-- .linkedin -->
	</ul>
</div><!-- .social_media_icons -->
<?php // END Social Media Icons Template Part ?>

<?php // Call template-part by adding the following line to your template: ?>
<?php get_template_part( 'icons', 'social' ); ?>

<?php // Add to footer.php before closing body tag (</body>) ?>
<script src="//platform.twitter.com/widgets.js" type="text/javascript"></script>
<script type="text/javascript">
  (function() {
    var po = document.createElement('script'); po.type = 'text/javascript'; po.async = true;
    po.src = 'https://apis.google.com/js/plusone.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(po, s);
  })();
</script>

<!---
Soiket/Soiket is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
