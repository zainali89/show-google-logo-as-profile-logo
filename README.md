# show-google-logo-as-profile-logo

put this in search result page code
<?php 
if($user_data['google_logo_url']  && ($user['image_main_file'] == $w['default_profile_image'] || $user['image_main_file'] == $w['default_logo_image']))
	{
		$user['image_main_file'] = $user_data['google_logo'];
	}
?>
