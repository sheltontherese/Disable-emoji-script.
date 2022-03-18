# Disable-emoji-script.
Disable emoji script.
// Disable the emoji's
remove_action('wp_head', 'print_emoji_detection_script', 7);
remove_action('wp_print_styles', 'print_emoji_styles');
