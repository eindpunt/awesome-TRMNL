<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome TRMNL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![GitHub last commit](https://img.shields.io/github/last-commit/eindpunt/awesome-trmnl)


<!-- subtitle -->

A curated list of TRMNL docs, talks, tools, examples & articles the internet has to offer.
<!-- image -->
<a href="https://usetrmnl.com" target="_blank" rel="noopener noreferrer">
<picture>
  <source srcset="logo--white@512px.png" media="(prefers-color-scheme: dark)">
  <source srcset="logo--black@512px.png" media="(prefers-color-scheme: light)">
  
  <img src="logo--black@512px.png" alt="Logo">
</picture>
</a>

<!-- description -->
[TRMNL](https://usetrmnl.com/) (pronounced "terminal") is an innovative e-ink dashboard device designed to help users stay focused and informed
</div>

<!-- TOC -->

## Specifications TRMNL
- A 7.5" e-ink display (4 grayscale)
- An ESP32-C3 microcontroller
- A 1800-2500 mAh battery
- The server generates a single-use, 1-bit bitmap image (800x480 pixels)

## Specifications TRMNL X
- A 10.3" e-ink display (16 grayscale)
- A 5000-7000 mAh battery

<!-- CONTENT -->

## 📄 Official Docs & Quickstarts
- [useTRMNL](https://docs.usetrmnl.com/)
- [Terminus](https://github.com/usetrmnl/byos_hanami) - Self hosted screen generation in Ruby/Hanami maintained by the TRMNL team

## ⚡Firmware & Firmware flashing
  | Repository                                                                                  | Description                                                            | Creator    | Type     | Badge |
  | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------- | -------- | -------- |
  | [Alternative Firmware](https://github.com/covercash2/trmnl_rs)                              | Alternative firmware for the official TRMNL firmware with Rust and Nix | covercash2 | Firmware | Firmware |
  | [ESPHome firmware](https://github.com/jesserockz/esphome-trmnl)                             | ESPHome firmware for TRMNL                                             | jesserockz | Firmware | Firmware |
  | [Homeplate](https://github.com/lanrat/homeplate)                                            | Firmware for the Inkplate 10                                           | lanrat     | Firmware | Firmware |
  | [TRMNL browser firmware flashing](https://usetrmnl.com/flash)                               | Flash your TRMNL firmware in browser                                   | TRMNL      | Tool     | Firmware |
  | [TRMNL firmware](https://github.com/usetrmnl/firmware)                                      | Official TRMNL firmware                                                | usetrmnl   | Firmware | Firmware |
  | [WaveShare ESP32-WROOM epaper board TRMNL Firmware](https://github.com/JayJay1989/firmware) | TRMNL firmware for WaveShare ESP32-WROOM epaper board                  | JayJay1989 | Firmware | Firmware |

## 🖱️ Development
| Repository                                                                                    | Description                                | Creator       | Type      | Category    |
| --------------------------------------------------------------------------------------------- | ------------------------------------------ | ------------- | --------- | ----------- |
| [Azure DevOps Pull Requests](https://github.com/VanBelleRik/azure-devops-pull-requests-trmnl) | Fetches Azure DevOps pull requests         | VanBelleRik   | Plugin    | Development |
| [Emulate TRMNL display](https://github.com/jackmawer/virtual-trmnl)                           | Webpage to emulate the TRMNL display       | jackmawer     | Tool      | Development |
| [GitHub Workflows](https://github.com/jcorbalanm/trmnl-github-workflows)                      | Shows the last 100 GitHub workflows of a custom repo        | jcorbalanm    | Plugin    | Development |
| [Laravel TRMNL](https://github.com/bnussbau/laravel-trmnl)                                    | Develop TRMNL plugins with Laravel         | bnussbau      | Framework | Development |
| [LocalPaper](https://github.com/medo64/LocalPaper)                                   | Local composer for Trmnl device         | medo64      | Framework | Development |
| [OpenRouter Tracker](https://github.com/saysharastuff/openrouter-tracker)                     | Display OpenRouter usage data              | saysharastuff | Plugin    | Development |
| [Plugin Tester](https://github.com/gitstua/trmnl-plugin-dev)                                  | Development tool for testing TRMNL plugins | gitstua       | Tool      | Development |
| [Plugin DEV kit](https://github.com/sdjmchattie/trmnl-plugin-dev-kit)                         | Plugin development kit for TRMNL devices   | sdjmchattie   | Framework | Development |
| [Sentry Monitor](https://github.com/kraynel/trmnl-sentry)                                     | Display Sentry project metrics             | kraynel       | Plugin    | Development |

## 🔨 Development - Boilerplates
| Repository                                                              | Description                                  | Creator      | Type        | Category    |
| ----------------------------------------------------------------------- | -------------------------------------------- | ------------ | ----------- | ----------- |
| [TRMNL hello (liquid)](https://github.com/schrockwell/trmnl-hello)      | Boilerplate for the trmnl_preview dev server | schrockwell  | Boilerplate | Development |
| [Python Boilerplate](https://github.com/OptimumMeans/TRMNL-Boilerplate) | Python boilerplate for TRMNL                 | OptimumMeans | Boilerplate | Development |

## 🔌 Plugins - General
| Repository                                                                                                        | Description                                                      | Creator               | Type   | Category         | Countries |
| ----------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | --------------------- | ------ | ---------------- | --------- |
| [useTRMNL](https://github.com/usetrmnl/plugins)                                                                   | Featured TRMNL plugins                                           | useTRMNL              | Plugin | Utilities        | Global    |
| [trmnl-recipe-catalog](https://bnussbau.github.io/trmnl-recipe-catalog)                                           | Community-driven catalog of TRMNLP-compatible recipes            | bnussbau              | Plugin | Lifestyle        | Global    |
| [Adafruit IO](https://github.com/stephenyeargin/trmnl-adafruit-io)                                                | Adafruit IO integration                                          | stephenyeargin        | Plugin | IoT              | Global    |
| [American College Football top 10](https://github.com/SnarfulSolutionsGroup/TRMNL-Plugins/blob/main/TRMNL_CFB.md) | College Football top 10 ranking                                  | SnarfulSolutionsGroup | Plugin | Sports           | USA       |
| [Anime of the Day](https://github.com/Saious119/trmnl-anime-of-the-day/tree/main)                                 | Displays a random anime of the day from Anilist                  | Saious119             | Plugin | Entertainment    | Global    |
| [Anker Solix Battery Bridge](https://github.com/makurix/anker-trmnl-bridge)                                       | Display Anker Solix battery stats                                | makurix               | Plugin | IoT / Smart Home | Global    |
| [Anki Cards](https://github.com/ItsJustThomas/trmnl-anki)                                                         | Display Anki flashcards                                          | ItsJustThomas         | Plugin | Education        | Global    |
| [Apple Photos](https://github.com/zegl/trmnl-apple-photos)                                                        | Display Apple Photos library                                     | zegl                  | Plugin | Productivity     | Global    |
| [Apple Reminders](https://github.com/sdjmchattie/trmnl-apple-reminders)                                           | Display Apple Reminders tasks                                    | sdjmchattie           | Plugin | Productivity     | Global    |
| [Baseball schedule: St. Louis Cardinals](https://github.com/kevdog114/trmnl_stlcards)                             | Fetch St. Louis Cardinals baseball schedule & standings          | kevdog114             | Plugin | Sports           | USA       |
| [Bart Departure (California)](https://github.com/oaklandgit/TRMNL_BART_Plugin)                                    | Get BART departure times                                         | oaklandgit            | Plugin | Transit          | USA       |
| [Berlin's BVG Transit](https://github.com/danmunoz/trmnl-bvg-transit)                                             | Monitors Berlin's BVG public transportation                      | danmunoz              | Plugin | Transit          | Germany   |
| [Block Clock](https://github.com/tyler-dot-earth/trmnl-notblockclock)                                             | A block clock display                                            | tyler-dot-earth       | Plugin | Utilities        | Global    |
| [Bookclub planner](https://github.com/bnussbau/trmnl-bookclub-planner)                                            | Plan and track book club reading                                 | bnussbau              | Plugin | Lifestyle        | Global    |
| [Bouldering Gym: Check how busy it is](https://github.com/tquin/trmnl-bouldering)                                 | Displays current occupancy of bouldering gyms via rockgympro.com | tquin                 | Plugin | Sports / Fitness | USA       |
| [Bundesliga Results](https://github.com/philippheldt/TRMNL_Bundesliga-Results)                                    | Displays Bundesliga matchday fixtures and tables                 | philippheldt          | Plugin | Sports           | Germany   |
| [Calibre e-book dashboard](https://github.com/goodlibbin/trmnl-calibre-template)                                  | Display Calibre-web library stats on TRMNL e-ink                 | goodlibbin            | Plugin | Productivity     | Global    |
| [Chuck Norris facts](https://github.com/OptimumMeans/TRMNL-Chuck-Norris)                                          | Random Chuck Norris facts                                        | OptimumMeans          | Plugin | Entertainment    | Global    |
| [Countdown plugin](https://github.com/jvdmeij/trmnl-countdown)                                      | Countdown to a specific date with emoji and text        | jvdmeij               | Plugin | Utilities                    | Global    |
| [Crypto Fear & Greed](https://github.com/jvdmeij/trmnl-crypto-fear-and-greed)                       | Displays crypto market fear & greed using Alternate API | jvdmeij               | Plugin | Finance / Crypto             | Global    |
| [Cyber Security conferences](https://github.com/AlixAbbasi/TRMNL-Sec-Deadlines)                     | Cyber security conference deadlines                     | AlixAbbasi            | Plugin | Education / Security         | Global    |
| [Daily comic xkcd](https://github.com/SnarfulSolutionsGroup/TRMNL-Plugins/blob/main/TRMNL_Comic.md) | Daily comic from xkcd                                   | SnarfulSolutionsGroup | Plugin | Entertainment                | Global    |
| [Digital Archaeologist](https://github.com/OptimumMeans/TRMNL-Digital-Archaeologist)                | Digital Archaeologist                                   | OptimumMeans          | Plugin | Education / History          | Global    |
| [Discord Bot](https://github.com/OptimumMeans/TRMNL-Discord-Bot)                                    | Discord bot integration                                 | OptimumMeans          | Plugin | Productivity / Communication | Global    |
| [Europe League Results](https://github.com/philippheldt/TRMNL_Europa_League-Results)                | Displays Europa League group & knockout stage tables    | philippheldt          | Plugin | Sports                       | Europe    |
| [FBI most wanted](https://github.com/OptimumMeans/TRMNL-FBI-Most-Wanted)                            | Random info on FBI Most Wanted fugitives                | OptimumMeans          | Plugin | Law / Education              | USA       |
| [Fathom Analytics](https://github.com/rknightuk/trmnl-fathom-analytics)                             | Fathom Analytics integration                            | rknightuk             | Plugin | Analytics / Web              | Global    |
| [Focus Blocks](https://github.com/btertoolen/trmnl_focus_blocks_plugin)                             | Focus time block tracker                                | btertoolen            | Plugin | Productivity                 | Global    |
| [Foxhole maps](https://github.com/stedrow/foxhole-trmnl-dashboard)                                  | Foxhole game war status maps                            | Stedrow               | Plugin | Gaming                       | Global    |
| [Fruit Facts](https://github.com/OptimumMeans/TRMNL-Fruit-Facts)                                    | Random fruit facts                                      | OptimumMeans          | Plugin | Education / Fun              | Global    |
| [GitHub Commit Graph](https://github.com/usetrmnl/plugins/tree/master/lib/github_commit_graph)      | GitHub commit tracker graph                             | useTRMNL              | Plugin | Productivity / Analytics     | Global    |
| [Goals Manager](https://github.com/nmartinovic/trmnl-goals-manager)                                 | Personal goals manager                                  | nmartinovic           | Plugin | Productivity                 | Global    |
| [Goodreads progress](https://github.com/goodlibbin/trmnl-goodreads)                               | Track Goodreads reading progress                             | goodlibbin       | Plugin | Lifestyle / Education       | Global      |
| [Google Keep todo list](https://github.com/ellipticview/trmnl-google-keep)                        | Display Google Keep todo list                                | ellipticview     | Plugin | Productivity                | Global      |
| [Ground Control ISS data](https://github.com/vanbrabantf/Ground-Control-TRMNL)                    | Fetches International Space Station data                     | vanbrabantf      | Plugin | Science / Space             | Global      |
| [Habitica Tasks](https://github.com/thepeopleseason/trmnl-plugins/tree/main/habitica-tasks)       | Show all tasks from Habitica                                 | thepeopleseason  | Plugin | Productivity / Gamification | Global      |
| [Habitify](https://github.com/sejtenik/trmnl-habitify-plugin)                                     | Habit tracking via Habitify                                  | sejtenik         | Plugin | Productivity / Health       | Global      |
| [Hacker News](https://github.com/usetrmnl/plugins/tree/master/lib/hacker_news)                    | Hacker News feed display                                     | useTRMNL         | Plugin | News / Technology           | Global      |
| [Hardcover statistics](https://github.com/jacobtender/hardcover_trmnl)                            | Display Hardcover social network statistics for book lovers  | jacobtender      | Plugin | Lifestyle / Education       | Global      |
| [iCal Calendar Flask web service](https://github.com/shyamvenugopalan/trmnl-ical-calendar-server) | iCal Flask web service                                       | shyamvenugopalan | Plugin | Productivity / Calendar     | Global      |
| [ICS Calendar](https://github.com/jfsso/trmnl-calendar)                                           | Fetch and display ICS calendar events in multi-column format | jfsso            | Plugin | Productivity / Calendar     | Global      |
| [Japan 72 Seasons](https://github.com/pipwilson/trmnl-72-seasons)                                 | Display traditional 72 Japanese seasons                      | pipwilson        | Plugin | Culture / Education         | Japan       |
| [KEXP Playlist](https://github.com/modestindustries/TRMNL-Projects/tree/main/TRMNL-KEXP-Playlist) | Display KEXP radio playlist                                  | modestindustries | Plugin | Entertainment / Music       | USA         |
| [KR TV guide](https://github.com/JJGrootveld/trmnl-kr-tvguide)                                    | Fetch daily Korean TV schedules (tv.kt.com)                  | JJGrootveld      | Plugin | Entertainment / TV          | South Korea |
| [LastFM last listened](https://github.com/monsieurm/trmnl-lastfm)                                 | Get LastFM last track listened and user info                 | monsieurm        | Plugin | Entertainment / Music       | Global      |
| [LastFM](https://github.com/rknightuk/trmnl-lastfm)                                               | LastFM dashboard display                                     | rknightuk        | Plugin | Entertainment / Music       | Global      |
| [Libra weight tracker](https://github.com/sejtenik/trmnl-libra-cloud-plugin)                | Displays Libra weight tracker    | sejtenik          | Plugin | Productivity / Health       | Global    |
| [Lumon Wellness facts](https://github.com/vimwtf/trmnl-lumon-wellness)                            | Display facts about your Outie                | vimwtf          | Plugin | Education / Fun              | Global    |
| [MBTA Transport](https://github.com/RyanAngelo/trmnl-mbta)                             | A real-time MBTA (Massachusetts Bay Transportation Authority) schedule display application                            | RyanAngelo          | Plugin | Transportation              | USA       |
| [MEH Deals](https://github.com/ajchili/meh-deals-trmnl-plugin)                                    | Display the daily deal(s) from meh.com                | ajchili          | Plugin | Shopping / Deals              | Global    |
| [Magic 8-Ball](https://github.com/jvdmeij/trmnl-magic-8-ball)                                  | Let the Magic 8-Ball make your decisions                | jvdmeij          | Plugin | Fun / Entertainment              | Global    |
| [Malware Trending](https://github.com/youkergav/TRMNL-Malware-Trending-Plugin)                            | Malware Trending plugin                | youkergav          | Plugin | Security / Tech              | Global    |
| [Mario Kart tracks](https://github.com/rknightuk/trmnl-mario-kart)                             | shows random Mario Kart tracks                | rknightuk          | Plugin | Gaming / Fun              | Global    |
| [Marvel Character of the Day](https://github.com/MarkHopper24/Marvel-Character-of-the-Day/)      | Marvel Character of the Day                | MarkHopper24          | Plugin | Entertainment / Comics     | Global    |
| [Marvel Comic Tracker](https://github.com/Saious119/trmnl-marvel-comic-tracker)                            | Based on a user defined list display what Marvel comics are coming out this week                | Saious119          | Plugin | Entertainment / Comics     | Global    |
| [Marvel Rivals Stat Tracker](https://github.com/MarkHopper24/Marvel-Rivals-TRMNL-Tracker)      | Track your Marvel Rival stats on your TRMNL device                | MarkHopper24          | Plugin | Gaming / Entertainment     | Global    |
| [Matomo Analytics](https://github.com/stephenyeargin/trmnl-matomo)                             | Matomo Analytics dashboard (Google Analytics alternative)                | stephenyeargin          | Plugin | Analytics / Web              | Global    |
| [Metar Weather](https://github.com/schrockwell/trmnl-metar)                                  | Displaying Weather conditions for a METAR station (METeorologial Aerodrome Reports), data is provided by NOAA's Aviation Weather Center                | schrockwell          | Plugin | Weather              | Global    |
| [Metrofresh soups](https://github.com/Bartlebyy/trmnl-plugin-metrofresh-soups)                            | An Express service that fetches the daily soup menu from MetroFresh via Menuat                | Bartlebyy          | Plugin | Food / Recipes              | Global    |
| [Money Rates (St. Louis Federal Reserve)](https://github.com/dmlandin/TRMNLmoneyRates)                             | Money rates dashboard                | dmlandin          | Plugin | Finance / Economics     | USA       |
| [Moonphase display](https://github.com/schrockwell/trmnl-moonphase)                                  | Displays the current Moon Phase                | schrockwell          | Plugin | Astronomy / Science     | Global    |
| [NASA Deep Space Network](https://github.com/schrockwell/trmnl-dsn)                             | Deep Space Network statistics                | schrockwell          | Plugin | Space / Science     | Global    |
| [NHL Next game](https://github.com/cbdm/trmnl-plugins/tree/main/nhl-teams-next-game)      | NHL Next game                | cbdm          | Plugin | Sports / Hockey     | North America    |
| [Nashville Fire Department Incidents](https://github.com/stephenyeargin/trmnl-nfd-incidents)                            | Nashville Fire Department Active Incidents                | stephenyeargin          | Plugin | Emergency Services     | USA       |
| [Nashville Police Dept. Active Dispatches (Metro)](https://github.com/stephenyeargin/trmnl-mnpd-dispatches)                             | Metro Nashville Police Dept. Active Dispatches                | stephenyeargin          | Plugin | Emergency Services     | USA       |
| [Nightscout - blood sugar data](https://github.com/gabe565/trmnl-nightscout)                                  | TRMNL Nightscout fetches blood sugar data from Nightscout                | gabe565          | Plugin | Health / Medical     | Global    |
| [ÖBB Train monitor](https://github.com/bnussbau/trmnl-train-monitor)                             | Austrian ÖBB / OBB Train monitor                | bnussbau          | Plugin | Transportation     | Austria    |
| [OGhunt](https://github.com/Hacksore/oghunt-trmnl)                                  | A plugin to show the top five product hunt launches without AI                | Hacksore          | Plugin | Tech / Productivity     | Global    |
| [Obsidian](https://github.com/frethop/obsidian-TRMNL)                             | Sample plugin to show Obsidian data on trmnl                | frethop          | Plugin | Productivity / Note-taking     | Global    |
| [PagerDuty Display](https://github.com/thepeopleseason/trmnl-plugins/tree/main/oncalltoday)      | Are you on call today with PagerDuty?                | thepeopleseason          | Plugin | Work / Productivity     | Global    |
| [Postmark challenge](https://github.com/schrockwell/trmnl-postmark-challenge)                                  | Postmark challenges                | schrockwell          | Plugin | Tech / Security     | Global    |
| [PS2 title screens](https://github.com/rknightuk/trmnl-ps2-title-screens)                             | Display random PS2 title screens                | rknightuk          | Plugin | Gaming / Retro     | Global    |
| [Remember The Milk](https://github.com/sejtenik/trmnl-rtm-plugin)                                  |                | sejtenik          | Plugin | Productivity / Task Management     | Global    |
| [STRMNL - Strava activties ](https://strmnl.app/)                            | Strava activities and stats                | paneq          | Plugin | Sports / Fitness     | Global    |
| [SV Eevee Prices (Pokemon)](https://github.com/lannonbr/trmnl-sv-eevee-prices)                                  | Displays Eeveelution prices from Terastal Festival ex & Prismatic Evolutions                | lannonbr          | Plugin | Gaming / Pokemon     | Global    |
| [Salah Prayer Times](https://github.com/abshirahmed/trmnl-salah-times)                             |                | abshirahmed          | Plugin | Religion / Education     | Global    |
| [SAT GUS Tracker](https://github.com/loesak/trmnl_satgus)                                  | Easily track SAT GUS                | loesak          | Plugin | Education / Productivity     | Global    |
| [Seatgeek upcoming events](https://github.com/stephenyeargin/trmnl-seatgeek)                             | Seatgeek upcoming events                | stephenyeargin          | Plugin | Entertainment / Events     | Global    |
| [Shipping Tracker](https://github.com/OptimumMeans/TRMNL-Ship-Tracker)                | Ship tracker using VesselFinder API                | OptimumMeans          | Plugin | Transportation     | Global    |
| [Sleeper Standing](https://github.com/bnussbau/trmnl-sleeper-standings)                             | TRMNL Hackaton winner, see your weekly matchups and vital stats about your competitor                | bnussbau          | Plugin | Sports / Fantasy Football     | Global    |
| [Star Wars newsfeed](https://github.com/mc-cari/trmnl-starwars-book-feed)                                  | Star Wars news about Comic & Books                | mc-cari          | Plugin | Entertainment / News     | Global    |
| [Steam deals](https://github.com/subtype-space/trmnl-steam-deals)                             | Displays top rated Steam deals                | subtype-space          | Plugin | Gaming / Deals     | Global    |
| [Steam sales](https://github.com/andrzejskowron/trmnl-steamsales)                                  | Snatch a Steam sale                | andrzejskowron          | Plugin | Gaming / Sales     | Global    |
| [Stock price](https://github.com/usetrmnl/plugins/tree/master/lib/stock_price)                             | Stock price                | usetrmnl          | Plugin | Finance / Markets     | Global    |
| [Strava goals](https://github.com/vinayak-mehta/trmnl-strava-goals)                                  | Strava goals                | vinayak-mehta          | Plugin | Sports / Fitness     | Global    |
| [Surf (surfline) display](https://github.com/pcifaldi/surf_api)                             | real-time surf and tide data display                | pcifaldi          | Plugin | Sports / Weather     | Global    |
| [Swedish Weather Service](https://github.com/frjo/usetrmnl-plugins/tree/main/smhi)                                  | Swedish weather service                | frjo          | Plugin | Weather     | Europe    |
| [TRMNL Quotes](https://github.com/michaelgilch/trmnl-quotes)                             | Inspirational Quotes                | michaelgilch          | Plugin | Inspiration / Fun     | Global    |
| [TRMNL Tides](https://github.com/UpDryTwist/trmnl-tides)                                  | Generate local tides screen on your TRMNL                | UpDryTwist          | Plugin | Weather / Science     | Global    |
| [TV Guide KT.com](https://github.com/JJGrootveld/trmnl-kr-tvguide)                             | TV Guide Plugin - KT Schedules                | JJGrootveld          | Plugin | Entertainment / TV     | Global    |
| [Telegram Image Forwarder](https://github.com/yazdipour/trmnl-telegram-bot)                                  | forward images from Telegram directly to a TRMNL                | yazdipour          | Plugin | Communication / Social     | Global    |
| [Tempest Weather Station](https://github.com/usetrmnl/plugins/tree/master/lib/tempest_weather_station)                             | Tempest Weather station                | usetrmnl          | Plugin | Weather     | Global    |
| [Teslamate Reporter](https://github.com/eden881/trmnl-teslamate-reporter)                                  | Display your Tesla statistics on your TRMNL                | eden881          | Plugin | Automotive / Tech     | Global    |
| [This day](https://github.com/frethop/TRMNL-thisday)                             | On This Day in history                | frethop          | Plugin | Education / History     | Global    |
| [TickTick Calendar](https://github.com/frethop/TRMNL-ticktick)                                  | TickTick Calendar                | frethop          | Plugin | Productivity / Calendar     | Global    |
| [Tidbyt sync](https://github.com/jvivona/tidbyt-data)                             | Synchronize your Tidbyt data                | jvivona          | Plugin | Tech / IoT     | Global    |
| [Todoist Sync](https://github.com/Nynir/trmnl-todoist)                                  | Synchronize your Todoist tasks                | Nynir          | Plugin | Productivity / Task Management     | Global    |
| [Transport for London status](https://github.com/stevekennedyuk/trmnl-tfl-status)                             | Transport for London status                | stevekennedyuk          | Plugin | Transportation     | London, UK    |
| [Uptime robot (websites)](https://github.com/stephenyeargin/trmnl-uptimerobot)                                  | UptimeRobot for TRMNL                | stephenyeargin          | Plugin | Tech / Monitoring     | Global    |
| [Valorant Tracker](https://github.com/MarkHopper24/Valorant-Tools)                             | Track your Valorant game stats                | MarkHopper24          | Plugin | Gaming / Esports     | Global    |
| [Vienna Metro Departures](https://github.com/bnussbau/trmnl-vienna-metro-departures)                                  | Vienna Metro (Wiener Linien) Departures                | bnussbau          | Plugin | Transportation     | Vienna, Austria    |
| [Washington Post frontpage](https://github.com/thamarnan/TRMNL-NYT)                             | Daily Washington Post frontpage                | thamarnan          | Plugin | News / Media     | USA       |
| [Weekly goal tracker / Habit tracker](https://github.com/azjgard/trmnl-weekly-goal-tracker)                                  | Weekly goal tracker                | azjgard          | Plugin | Productivity / Goals     | Global    |
| [Wego transit](https://github.com/transitnownash/trmnl-wego-next-trip)                             | WeGo Public Transit Next Trip                | transitnownash          | Plugin | Transportation     | Global    |
| [Who's that Pokemon](https://github.com/sriniketh/trmnl-plugin-whos-that-pokemon)                                  | Displays a random Pokémon every day                | sriniketh          | Plugin | Gaming / Fun     | Global    |
| [Whoop](https://github.com/sapochat/whoop-trmnl)                             | Whoop health recovery dashboard                | sapochat          | Plugin | Health / Fitness     | Global    |
| [Winnie the Pooh quote](https://github.com/jvdmeij/trmnl-winnie-the-pooh)                                  | A random quote by Winnie or one of his friends                | jvdmeij          | Plugin | Fun / Quotes     | Global    |
| [Wisdom Quotes](https://github.com/VisualYeti/wisdom_trmnl)                             | Display a daily quote from Merlin Mann's "The Wisdom Project"                | VisualYeti          | Plugin | Inspiration / Fun     | Global    |
| [Woocommerce](https://github.com/yannicschuller/trmnl-woocommerce)                                  | Fetches store data from WooCommerce API and displays                | yannischuller          | Plugin | E-commerce / Shopping     | Global    |
| [Word Clock](https://github.com/jvdmeij/trmnl-word-clock)                                  | The Word Clock tells in simple words what the time is                | jvdmeij          | Plugin | Fun / Time     | Global    |
| [Word clock](https://github.com/delhoume/trmnl_wordclock)                             | Word clock                | delhoume          | Plugin | Fun / Time     | Global    |
| [Words of the Day](https://github.com/sejtenik/trmnl-words-of-the-day-plugin)                                  | retrieves the Word of the Day from various online dictionaries                | sejtenik          | Plugin | Education / Language     | Global    |
| [YNAB](https://github.com/turnervink/ynab-for-trmnl)                             | See your YNAB budget (You Need a Budget) on your TRMNL                | turnervink          | Plugin | Finance / Budgeting     | Global    |
| [Year in Progress](https://github.com/monsieurm/trmnl-yearinprogress)                                  | Shows the progress of the year (dots or bar)                | monsieurm          | Plugin | Productivity / Goals     | Global    |
| [Your Life in Weeks](https://github.com/jvdmeij/trmnl-your-life-in-weeks)                                  | See the amount of weeks you have lived, and will live                | jvdmeij          | Plugin | Fun / Reflection     | Global    |


## 👨‍💻 Plugins - Homelab (for IT tech enthusiasts)
| Repository                                                                       | Description               | Creator        | App   | Category |
| -------------------------------------------------------------------------------- | ------------------------- | -------------- | ------ | -------- |
| [Beszel Monitor](https://github.com/yazdipour/trmnl-beszel)                      | Beszel server monitoring  | yazdipour      | Beszel | Homelab  |
| [Docker Container](https://github.com/rish2jain/Docker-TRMNL-Plugin)             | Monitor Docker containers | rish2jain      | [![Docker](https://img.shields.io/badge/docker-grey?style=for-the-badge&logo=docker)](#) | Homelab  |
| [Grafana Dashboards](https://github.com/DefCon-007/grafana-trmnl-plugin)         | Render Grafana dashboards (Flask) | DefCon-007     | [![Grafana](https://img.shields.io/badge/grafana-grey?style=for-the-badge&logo=grafana)](#) | Homelab  |
| [Kuma Uptime](https://github.com/bnussbau/trmnl-uptimekuma)                      | Monitor Uptime Kuma       | bnussbau       | Uptime Kuma | Homelab  |
| [Pi-Hole stats](https://github.com/JBertaux/pi-trmnl)                            | Pi-hole statistics        | JBertaux       | Pi-Hole | Homelab  |
| [Pixelfed](https://github.com/stephenyeargin/trmnl-pixelfed)                     | Displays pixelfed images  | stephenyeargin | Pixelfed | Homelab  |
| [Proxmox Backups](https://github.com/MartinBelko/TRMNL-Plugin-Proxmox-Backups)   | View results of recent backups (vzdumps) from your Proxmox VE nodes  | MartinBelko | [![Proxmox](https://img.shields.io/badge/proxmox-grey?style=for-the-badge&logo=proxmox)](#) | Homelab  |
| [Tailscale](https://github.com/stephenyeargin/trmnl-tailscale)                   | Tailscale dashboard       | stephenyeargin | [![Tailscale](https://img.shields.io/badge/tailscale-grey?style=for-the-badge&logo=tailscale)](#) | Homelab  |
| [Tautulli Dashboard](https://github.com/hosfordryan/trmnl-tautulli-dash)         | Tautulli Dashboard (Plex server user metrics)      | hosfordryan | Tautulli / Plex | Homelab  |
| [Unifi Site Manager](https://github.com/stephenyeargin/trmnl-unifi-site-manager) | Unifi site overview       | stephenyeargin | Unifi | Homelab  |

## 🏠 Plugins - Smart Home (Home Assistant, Energy)
| Repository                                                                                           | Description                                         | Creator         | Type   | Category    | Countries      |
| ---------------------------------------------------------------------------------------------------- | --------------------------------------------------- | --------------- | ------ | ----------- | -------------- |
| [Alto National Water Prediction Service Gauges](https://github.com/stephenyeargin/trmnl-nwps-gauges) | National Water Prediction Service gauges            | stephenyeargin  | Plugin | Environment | USA            |
| [Ambient Weather display](https://github.com/evandhoffman/trmnl-pws)                                 | AmbientWeather.net weather station display          | evandhoffman    | Plugin | Weather     | Global         |
| [Bring!](https://github.com/yshrdbrn/trmnl-bring-plugin)                                             | Bring! shopping list display                        | yshrdbrn        | Plugin | Smart Home  | Global         |
| [Buienradar](https://github.com/Akisame-AI/TRMNL_buienradar)                                         | Buienradar weather display                          | Akisame-AI      | Plugin | Weather     | Netherlands, Belgium    |
| [Dcache](https://github.com/ramdacxp/dcache)                                                         | Visualize selected Home Assistant entities          | ramdacxp        | Plugin | Smart Home  | Global         |
| [Garbage Collector calendar](https://github.com/hrdkbhatnagar/trml-garbage-calendar)                 | Worldwide garbage collection calendar               | hrdkbhatnagar   | Plugin | Utilities   | Global         |
| [HACS Sensor push](https://github.com/gitstua/trmnl-sensor-push)                                     | Home Assistant HACS component pushing data to TRMNL | gitstua         | Add-on | Smart Home  | Global         |
| [Home Assistant Addon](https://github.com/ohAnd/trmnlServer_ha_addon)                                | Home Assistant addon for TRMNL                      | ohAnd           | Add-on | Smart Home  | Global         |
| [Home Assistant](https://github.com/ididit99/useTRMNL-Home-Assistant)                                | Send Home Assistant data via webhook                | ididit99        | Plugin | Smart Home  | Global         |
| [Home Assistant](https://github.com/fisherevans/ha2trmnl)                                            | Home Assistant data integration for TRMNL           | fisherevans     | Plugin | Smart Home  | Global         |
| [Home Assistant Entities](https://github.com/pwojtaszko/trmnl-home-assistant-plugin)                 | Display Home Assistant entities with custom layouts | pwojtaszko      | Plugin | Smart Home  | Global         |
| [Nashville Pollen & Air Quality](https://github.com/stephenyeargin/trmnl-nashville-pollen-aqi)       | Nashville pollen & air quality display              | stephenyeargin  | Plugin | Health      | USA            |
| [Octopus Energy usage](https://github.com/marksankey/Energy_Usage)                                   | Octopus Energy usage dashboard (UK)                 | marksankey      | Plugin | Energy      | UK |
| [Open-Meteo Hourly Weather](https://github.com/andi4000/trmnl-open-meteo-weather-forecast)           | Hourly weather forecast from Open-Meteo             | andi4000        | Plugin | Weather     | Global         |
| [Pollen Forecast Europe](https://github.com/bnussbau/trmnl-pollen-forecast-eu)                       | Pollen forecast for Europe                          | bnussbau        | Plugin | Health      | Europe         |
| [Tibber Norway](https://github.com/MartinBelko/TRMNL-Plugin-Tibber-Norway)                           | Hourly electricity prices for Tibber Norway         | MartinBelko     | Plugin | Energy      | Norway         |
| [Wasserspiegel](https://github.com/timgluz/wasserspiegel)                                            | Current water level display                         | timgluz         | Plugin | Environment | Germany        |
| [Wttr.in display](https://github.com/thepeopleseason/trmnl-plugins/tree/main/wttr.in)                | Weather display from wttr.in                        | thepeopleseason | Plugin | Weather     | Global         |
| [YoLink Temperature](https://github.com/erikbuild/trmnl-yolink-temperature)                          | YoLink temperature sensor display                   | erikbuild       | Plugin | Smart Home  | USA            |
| [Zonneplan](https://github.com/LeipeLeon/zonneplan)                                                  | 🇳🇱 Zonneplan dynamic energy pricing tracker       | LeipeLeon       | Plugin | Energy      | Netherlands    |


## 📺 Screen generators
| Repository                                                                        | Description               | Creator    | Type   | Category  |
| --------------------------------------------------------------------------------- | ------------------------- | ---------- | ------ | --------- |
| [Alias Plugin](https://help.usetrmnl.com/en/articles/10701448-alias-plugin)       | Alias screen plugin       | TRMNL      | Screen | Generator |
| [Image Screen Generator](https://github.com/noahcreany/TRMNL_screens)             | TRMNL screens             | noahcreany | Screen | Generator |
| [Redirect Plugin](https://help.usetrmnl.com/en/articles/11035846-redirect-plugin) | Redirect screen plugin    | TRMNL      | Screen | Generator |



## 👾 Extra's

| Repository                                                          | Description                         | Creator     | Type          | Category |
| ------------------------------------------------------------------- | ----------------------------------- | ----------- | ------------- | -------- |
| [Android Mirror](https://github.com/usetrmnl/trmnl-android)         | Mirror TRMNL content to Android,originally developed by hossain-khan     | usetrmnl    | App           | Extra    |
| [BYOS Server (Laravel)](https://github.com/usetrmnl/byos_laravel)      | Build Your Own Server using Laravel | ghcpuman902 | Server        | Extra    |
| [BYOS Server (Next.js)](https://github.com/usetrmnl/byos_next)      | Build Your Own Server using Next.js | ghcpuman902 | Server        | Extra    |
| [BYOS Server (Ruby / Hanami)](https://github.com/usetrmnl/byos_hanami)      | Build Your Own Server using Ruby | usetrmnl | Server        | Extra    |
| [Build your own TRMNL](https://github.com/ruohki/makeshift-trmnl)      | Makeshift edition | ruohki | Server        | Extra    |
| [Chrome extension](http://github.com/usetrmnl/trmnl-chrome)      | Display images from TRMNL's API in your new Chrome tab | usetrmnl | App        | Extra    |
| [Convert Kindle to TRMNL](https://github.com/usetrmnl/trmnl-kindle) | Turn Kindle into TRMNL              | usetrmnl    | Hardware Hack | Extra    |
| [Convert Kobo to TRMNL](https://github.com/usetrmnl/trmnl-kobo) | Turn Kobo into TRMNL              | usetrmnl    | Hardware Hack | Extra    |
| [Convert Nook to TRMNL](https://github.com/usetrmnl/trmnl-nook) | Turn Nook into TRMNL              | usetrmnl    | Hardware Hack | Extra    |
| [Convert WaveShare to TRMNL](https://github.com/tobias-theobald/epd-node-trmnl)            | Turn WaveShare 7.5" V2 into TRMNL           | tobias-theobald     | Hardware Hack          | Extra    |
| [Kuroshiro](https://github.com/PhyberApex/kuroshiro) | Kuroshiro is an open-source BYOS (Bring Your Own Server)              | PhyberApex    | Server | Extra    |
| [Open Source server](https://github.com/GioPan04/opntrmnl/) | An open-source self-hostable alternative for trmnl plugins    | GioPan04    | Server | Extra    |
| [React based renderer](https://github.com/pascal-giguere/react-trmnl)            | A React-based renderer           | pascal-giguere     | Rendering          | Extra    |
| [Server for dashboard](https://github.com/donmccaughey/trmnl_srv)   | Python based server for TRMNL dashboard           | donmccaughey     | Tool          | Extra    |
| [TRMNL 3D printable mounts](https://github.com/usetrmnl/mounts)   | 3D printable mounts (fridge magnet, corner bracket) | usetrmnl | 3D Print | Extra
| [TRMNL Buddy](https://github.com/hossain-khan/trmnl-android-buddy)  | Monitor your TRMNL on the go with Android |hossain-khan | Tool | Extra
| [TRMNL docker](https://hub.docker.com/r/schrockwell/trmnlp) |  Docker image for local dev |  schrokwell | [![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff)](#) | Extra |
| [TRMNL Local Web Server](https://github.com/ohAnd/trmnlServer) | Python local webserver for TRMNL | ohAnd | Server | Extra
| [TRMNL Preview](https://github.com/schrockwell/trmnl_preview)       | Local development preview server (liquid templates)  | schrockwell | Tool          | Extra    |
| [TRMNL Tricks](https://github.com/yunruse/trmnl-tricks)             | Tips and tricks for TRMNL           | yunruse     | Docs          | Extra    |


<!-- END CONTENT -->

## 📽️ Video's
- [TRMNL OSS Server - Alpha Release Demo](https://www.youtube.com/watch?v=3xehPW-PCOM)

## Follow

### Official

- 📹 [TRMNL YouTube](https://www.youtube.com/@useTRMNL)
- 🐦 [@useTRMNL](https://x.com/useTRMNL)
- 👤 [TRMNL Facebook](https://www.facebook.com/useTRMNL)
- 📷 [TRMNL Instagram](https://www.instagram.com/usetrmnl/)
- 🖼️ [NEW TRMNL X](https://shop.usetrmnl.com/products/trmnl-x?mtke=30) A bigger TRMNL!
- 

### 🫂 Community

- 📺 [YouTube review](https://www.youtube.com/watch?v=eIcZZX10pa4)

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/eindpunt/awesome-trmnl/graphs/contributors)!
