# show-google-logo-as-profile-logo

// put this in search result page code
<?php 
$db_variable_name = 'google_logo';
if($user[$db_variable_name]  && ($user['image_main_file'] == $w['default_profile_image'] || $user['image_main_file'] == $w['default_logo_image']))
	{
		$user['image_main_file'] = $user[$db_variable_name];
	}
?>


// put this code in Bootstrap Theme - Member Profile - Header

<?php 
$db_variable_name = 'google_logo';
if($user[$db_variable_name]  && ($userPhoto == $w['default_profile_image'] || $userPhoto == $w['default_logo_image']))
	{
		$userPhoto = $user[$db_variable_name];
	}
?>
