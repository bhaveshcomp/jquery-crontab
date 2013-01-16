# jQuery plugin: crontab

jquery-crontab is a [jQuery] plugin for
presenting a simplified interface for users to specify cron entries.

Check out the [jquery-crontab] website for more information.

This plugin was developed to fulfil the requirements that arose
from the [BBotUI Project] by [shawnChin]. We added some specific functionality
and forked his project.
As such, while we do try to make the implementation as generic
as possible, we dare not claim this plugin to be as flexible
as one would expect a sensible jQuery plugin to be.

There is much to be done on the flexibility and robustness front,
and we welcome contributions and bug fixes. Feel free to fork
and send us pull requests!

## Dependencies

 * [jQuery]
 * [jquery-gentleSelect]

## Usage

To use this plugin, one simply needs to load [jQuery], [jquery-gentleSelect]
and the JS/CSS scripts for jquery-crontab, then attach it an empty `<DIV>`
on DOM ready:

    $(document).ready(function() {
        $('#selector').cron();
    });
    </script>

For more options, see the [jquery-crontab] website. We would like to record
thanks to the creator of the project Shawn Chin, which this project was originally
forked from.


## Others

Copyright (c) 2013, Low Kian Seong.

This project is licensed under the [MIT license].

 [jQuery]: http://jquery.com "jQuery"
 [shawnChin]: http://shawnchin.github.com/
 [jquery-crontab]: http://shawnchin.github.com/jquery-crontab "jquery-crontab"
 [BBotUI Project]: https://github.com/shawnchin/bbotui "BBotUI project"
 [jquery-gentleSelect]: http://shawnchin.github.com/jquery-gentleSelect "jquery-gentleSelect"
 [MIT License]: http://www.opensource.org/licenses/mit-license.php "MIT License"
