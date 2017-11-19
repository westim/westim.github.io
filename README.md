# Tim's website/blog 
Theme is the Autm-rb theme: https://github.com/kirqe/autm-rb
 
I relied on Github's instructions for setting up the environment: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

Here is the helpful website I used to get through the install process: https://devblast.com/b/create-a-static-websiteblog-with-jekyll-and-github-pages/

## Tools
* Jekyll
* Ruby
* Bundler

## Other Steps
1. I updated the Gemfile to avoid errors using the instructions here: http://talk.jekyllrb.com/t/what-is-this-error-that-i-am-receiving/722/2 
2. I added the following line to the Gemfile because Jekyll told me to while building:
```
gem "wdm", ">= 0.1.0" if Gem.win_platform? 
```
3. I left the sample markdown blog post for now. It will probably be useful, so I'll leave it there and maybe clean it up for easier use.
4. I removed some of the external links from `_data/personal.yml`, although I may add them back in eventually.

## Licensing

[MIT](https://github.com/railsr/autm-rb/blob/master/LICENSE)
