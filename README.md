Sample application to demonstrate the issue reported at https://github.com/excid3/madmin/issues/246#issuecomment-2589888395

![Screenshot 2025-01-18 at 11.41.47 AM.png](public/Screenshot%202025-01-18%20at%2011.41.47%E2%80%AFAM.png)

![Screenshot 2025-01-18 at 11.44.06 AM.png](public/Screenshot%202025-01-18%20at%2011.44.06%E2%80%AFAM.png)

Note: the rails server is running on port 3010 in these screenshots from the command:

```
PORT=3010 bin/rails server
```

All commands:

1. `rails _7.2.2.1_ new madmin-2-sprokets-sample-app` (Chose the latest Rails 7 because it would come with sprockets working out of the box, reducing any potential for other configuration issues)

2. `bundle install`

3. `rails g madmin:install`

4. Added `HomeController` so there was a route to use as the root_url
