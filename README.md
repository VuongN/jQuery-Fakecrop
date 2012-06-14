**jQuery-Fakecrop Plugin** takes a collection of images and automatically scale them to fit a custom-defined bounding box. This creates a "fake" cropping effect on those images; which produces convincing thumbnails.

For more information, please visit: http://vuongnguyen.com/fake-cropping-images-with-jquery.html

**Quick Start:**

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