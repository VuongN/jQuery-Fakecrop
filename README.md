**jQuery-Fakecrop Plugin** allows you to achieve the fake cropping effect of images.

**Usage:**

	<script src="/path/to/jquery-library.js"></script>
	<script src="/path/to/fakecrop.js"></script>
	<script>
		$(document).ready(function () {
			// for a filled square thumbnail
			$('img').fakecrop();
			// for a fixed width/height
			$('img').fakecrop({fill: false});
		});
	</script>