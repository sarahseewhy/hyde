# sarahseewhy

Github.io for Sarah C Y, me. All things writing and blog related.

## Technology 
This site is gratefully built using [Jekyll](https://jekyllrb.com/docs/github-pages/). 

## Design
The page's design is based on the Hyde theme:

> Hyde is a brazen two-column [Jekyll](http://jekyllrb.com) theme that pairs a prominent sidebar with uncomplicated content. It's based on [Poole](http://getpoole.com), the Jekyll butler.

Do visit their github pages for more details.

## Issue Tracker

Track issues and features for the site.

| To Do | Doing | Done|
|-------|-------|-----|
| Next | | |
| Add content from wordpress | | |
| Add content from google docs | | |
|  | | Add content to `/about` |
|  | | Remove "Related posts" section |
|  | | Turn off pagination as it's not necessary at this point. |
|  | | Ensure pagination works |
|  | | Change colour for links |
|  | | Move sidebar content further up |
|  | | Change font-family across site |
|  | | Add linked 'Read more' to blurbs which redirects to full post |
|  | | Fix font file being loaded over HTTPS. This is fixed by removing the link to the font. I plan to change the font anyway |
|  | | Remove Hyde icon from browser tab |
|  | | Figure out why `site.baseurl` is not being interpolated as `/`. Issue cause: `baseurl` is set in `_config.yml`. For pages with the url `<user>.github.io` the `baseurl` should be blank as it's not being used. A "/" can be appended to the `{{site.baseurl}` to fix the home path to `/`. Please see [here](https://byparker.com/blog/2014/clearing-up-confusion-around-baseurl/) and [here](https://software-carpentry.org/blog/2016/09/we-still-cant-have-nice-things.html) for more details. |
|  | | Fix broken "Home" link which doesn't redirect to `/`. Hard code baseurl as `/` in html files. |
|  | | Fix not found style sheet for blog posts (404). Issue cause: Missing `/` in the css href. |
|  | | Anchor sidebar title to top |





