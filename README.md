# Please-provide-a-valid-cache-path-error-in-laravel


- Ensure the below folders in storage directory:
  ```text
    logs
    framework
    framework/cache
    framework/cache/data
    framework/sessions
    framework/testing
    framework/views
  ```

- Below is a command-line snippet that does for you
  ```text
    cd storage
    mkdir logs
    mkdir framework
    mkdir framework/cache && framework/cache/data
    mkdir framework/sessions
    mkdir framework/testing
    mkdir framework/views
    chgrp -R www-data ../storage
    chown -R www-data ../storage
  ```
