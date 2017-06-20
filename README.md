# User Extension Sprinkle (UserFrosting 4.1)

Example sprinkle for extending the User class to contain additional fields.

## Install
`cd` into the sprinkle directory of UserFrosting and clone as submodule:
```
git submodule add git@github.com:userfrosting/extend-user.git extend-user
```

### Add to the sprinkle list
Edit UserFrosting `app/sprinkles.json` file and add `extend-user` to the sprinkle list to enable it.

### Update the assets build & composer

- Run `composer update` from the root project directory.

### Run migration

- Run `php bakery bake` from the root project directory.