octo-about-me-from-twitter
==========================

Twitter generated "about me" aside for [octopress](http://octopress.org/) blogging framework.

Loads a few data from your twitter profile (avatar, name, location & description) and displays it on the sidebar of your octopress blog.
Your blog will stay up to date with your twitter profile! **\o/**

## Setup

1- Clone this repository into `{path to your octopress blog}/source/_includes/custom/asides/` folder (or simply download `aboutmetwitter.html` file into it):

    # Assuming you're already in your octopress root folder
    > cd source/_includes/custom/asides
    > git clone git://github.com/dharFr/octo-about-me-from-twitter.git .

2- Edit your `_config.yml` file:
  - Add `custom/asides/aboutmetwitter.html` to the `default_asides` list.
  - Be sure that the `twitter_user` key is filled with your twitter user name

3- Regenerate your blog. 

Done.


## License


                DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                        Version 2, December 2004

    Everyone is permitted to copy and distribute verbatim or modified
    copies of this license document, and changing it is allowed as long
    as the name is changed.

                DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
      TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

    0. You just DO WHAT THE FUCK YOU WANT TO.