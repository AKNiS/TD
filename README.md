TDredesign
MY NOTES - working document

Most Important Features for daily use.

New Torrent list
Search
Stats

Forum & Chat for some people

DONATE button (important for ADMINS and site owners)

Pages which could be combined

Profile / Settings (including themes) / Invites / Bonus / InBox — All under Profile Forum Chat Jokes RSS Donate Logout

Because you’re using php you’re able to combine a lot of pages into sections on a single page.

For the torrent lists, I’ve proposing that we use a CSS3-powered Accordion-style feature (vertically) to allow the most amount of information to be accessed at once. The site would employ a 'main page' which would function more like an application in this sense.

Vertical Use for displaying torrents

I've edited this demo file (very basic, only essentially styling) >> verticalAccordian/Index.html When you click on a torrent it will load the full details under it. This way we can replace the advert strip at the top of the page, and instead the front page will load with the first tab of the Accordion already open. I believe this will actually load more ads in the long run, as clicking on a tab will load much faster than loading an entirely new page.

PAGINATION -- I think the 'latest' section should load all torrents that have been listed in the last 24 hours as the default, with a long/infinity scrolling page. At the bottom we have 'load earlier posts' which will load the following 24 hours, etc. We could possibly have this as a tweakable option? 12 hours, 1 week? Maybe a slider hidden amongst the bottom menu, eventually?

SCRAP tthe horizontal accordian at the top in favour of a pure css tabbed top panel. Here is a nice pure CSS option for loading CSS tabs. https://css-tricks.com/functional-css-tabs-re-revisited/

-- If we go with flexbox for the bottom & top border menues, then we could also employ this nice way of displaying the tabs using flexbox. http://codepen.io/vulpesigni/pen/yyZYNy?editors=110

I also like the idea of using FlexBox (https://css-tricks.com/snippets/css/a-guide-to-flexbox/) as a way of forcing the top and bottom menus and keeping the middle completely flexible. It also means we could load additional info (such as the forum or the chat window) over to the right of the page. SCRAP THIS, PULL THE SEARCH FUNCTIONS FROM THE TOP MENU AND ONTO THE SPACE ON THE RIGHT OF THE PAGE.

For now I have used the existing file format icons (480p, etc) however I propose we switch up to new, SVG icons. These will load faster and scale much nicer.
