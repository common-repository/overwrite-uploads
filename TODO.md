* If ever need to, can probably simplify this with some newer hooks that are available
	* wp_unique_filename
	* wp_handle_upload_prefilter
	* $overrides['unique_filename_callback'] in _wp_handle_upload()
	* pre_move_uploaded_file
	* pre_wp_unique_filename_file_list - https://core.trac.wordpress.org/changeset/48369
