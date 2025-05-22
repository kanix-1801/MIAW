<html>
<body>
<h1>hyy</h1>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DdM000005UzRO',
				'forClientSIte',
				'https://raptbottechnologiespvtltd24-dev-ed.develop.my.site.com/ESWforClientSIte1747906549907',
				{
					scrt2URL: 'https://raptbottechnologiespvtltd24-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://raptbottechnologiespvtltd24-dev-ed.develop.my.site.com/ESWforClientSIte1747906549907/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
