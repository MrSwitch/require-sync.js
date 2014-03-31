#Require-Sync

A synchronous module loader based on the AMD pattern. This means you can load stuff inline - if you must - e.g.

	<script src="require-sync.js" data-main="demo-module.js"></script>
	<script>
		// In AMD you would have had to wrap this in a `require` handler
		window.demo-module-function('Loaded');
	</script>
