# GRC.github.io

<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DU9000001QERl',
				'GRC_Web_deployment',
				'https://rentacar--grcdev.sandbox.my.site.com/ESWGRCWebdeployment1729507799088',
				{
					scrt2URL: 'https://rentacar--grcdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://rentacar--grcdev.sandbox.my.site.com/ESWGRCWebdeployment1729507799088/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
