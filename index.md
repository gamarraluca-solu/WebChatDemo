<html>
	<body>
		<script type='text/javascript'>
			function initEmbeddedMessaging() {
				try {
					embeddedservice_bootstrap.settings.language = 'es'; // For example, enter 'en' or 'en-US'
		
					embeddedservice_bootstrap.init(
						'00DD30000001VC5',
						'WebChat',
						'https://ferromax--uat.sandbox.my.site.com/ESWWebChat1745258388223',
						{
							scrt2URL: 'https://ferromax--uat.sandbox.my.salesforce-scrt.com'
						}
					);
				} catch (err) {
					console.error('Error loading Embedded Messaging: ', err);
				}
			};
		</script>
		<script type='text/javascript' src='https://ferromax--uat.sandbox.my.site.com/ESWWebChat1745258388223/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>  
	</body>
</html>
