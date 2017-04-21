# Book 'Em Danno

Aloha! It's about time bookstores got more exciting. Now, you can find all the fun of a classic police procedural and all the mellow vibes of Hawaii in one place, but also with books! We've got the newest books and reviews of the hottest text on the market. We'll see you soon. Aloha!

## Prerequisites

You will need one of the following server management programs properly installed on your computer.

* [MAMP](https://www.mamp.info/en/)
* [WAMP](http://www.wampserver.com/en/)
* [LAMP](https://www.apachefriends.org/index.html)

## Installation

**Step 1**: Clone this repository to your local computer

```console
git clone https://github.com/KWLEvans/Book-Em-Danno
```

**Step 2**: Using your server management software, import the `bookstore.sql.zip` file from `/sites/db-backup`

**Step 3**: Create a new user on the database using username: 'bookstore' and password: 'bookstore'; you can double check in sites/default/settings.php

**Step 4**: Ensure that your web server software's document root is set to the project's root directory and that the MySQL port is set to 8889

**Step 5**: Visit the app at [http://localhost:8889](http://localhost:8889).

## License

MIT License. Copyright 2017 Keith Evans
