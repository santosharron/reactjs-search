# Apply Filter Hook

From v4.0.9 Reactive pro provided hooks(apply filter) support.
In this docs we will discuss about the hooks we have provided and which one can be useful for you,

All the hooks are available in the below file
reactivepro -> app -> Graph.php &
reactivepro -> shortcodes -> preview.php

In the above file you will see that we have added `apply_filters` in many places.

### reactivepro_get_grid_all_data

The most important hook here is the `reactivepro_get_grid_all_data` with this hook you can modify any data needed to show your grid search result.

### reactivepro_get_all_users

With this hook you can modify the user data if you are using user search.

### reactivepro_get_user_grid_data

Can also be used to modify user data in the user search result.

For now we think only this one is useful for the user. If you want to know more about any hook feel free to reach out to support here https://redqsupport.ticksy.com/
