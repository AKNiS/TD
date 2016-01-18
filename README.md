TDredesign
MY NOTES 

(working document)


Most Important Features (for daily use)

- New Torrent list
- Search / Advanced Search
- Stats

- Forum & Chat (for some people)
- DONATE button (important for ADMINS and site owners)

[Pages which could be combined]
[All under Profile (Forum Chat Jokes RSS Donate Logout)]
  - Profile 
  - Settings (including themes) 
  - Invites 
  - Bonus 
  - InBox (displays number of unread emails in the menu)

Because you’re using php you’re able to combine a lot of pages into sections on a single page.

Top & Bottom Banner
Banners are locked to the top and bottom, framing the content. 
I also like the idea of using FlexBox (https://css-tricks.com/snippets/css/a-guide-to-flexbox/) as a way of forcing the top and bottom menus and keeping the middle completely flexible. 

At the top use a pure css tabbed top panel to display the Featured movies. 

-- If we do go with flexbox for the bottom & top border menues, then we could also employ this nice way of displaying the tabs using flexbox. http://codepen.io/vulpesigni/pen/yyZYNy?editors=110



Displaying Most Recent Torrents
For the torrent lists, I’ve proposing that we use a CSS3-powered Accordion-style feature (vertically) to allow the most amount of information to be accessed at once. The site would employ a 'main page' which would function more like an application in this sense.

Vertical Use for displaying torrents
I've edited this demo file (very basic, only essentially styling) >> verticalAccordian/Index.html When you click on a torrent it will load the full details under it. This way we can replace the advert strip at the top of the page, and instead the front page will load with the first tab of the Accordion already open. I believe this will actually load more ads in the long run, as clicking on a tab will load much faster than loading an entirely new page.

PAGINATION
I think the 'latest' section should load all torrents that have been listed in the last 24 hours as the default, with a long/infinity scrolling page. At the bottom we have 'load earlier posts' which will load the following 24 hours, etc. We could possibly have this as a tweakable option? 12 hours, 1 week? Maybe a slider hidden amongst the bottom menu, eventually?

Icons / UI 
For now I have used the existing file format icons (480p, etc) however I propose we design new, SVG icons. These will load faster and scale much nicer.
