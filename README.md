# oodaris/.github

This repository holds the OODARIS organization profile. [`profile/README.md`](profile/README.md) is the page [github.com/oodaris](https://github.com/oodaris) shows, and [`profile/assets/`](profile/assets) holds its images.

## Keeping the profile in step with oodaris.ai

The profile repeats a few facts from [oodaris.ai](https://oodaris.ai/en), in the site's own words. When the site changes, check these and update the profile in the same week:

- the description of OODARIS and what it does each night;
- the ten capabilities and what each one proposes;
- the measured ranges and their method line;
- the agents, the integrations and the levels of autonomy;
- the books and the open roles;
- every link.

The profile names no customer, lists all ten capabilities as available, and keeps the headline "Built in retail. Not built for." as it is. Then set the date in the comment at the end of `profile/README.md` to the "Last updated" date of [llms-full.txt](https://oodaris.ai/llms-full.txt).

The [Profile README](.github/workflows/profile-readme.yml) workflow checks that each image the profile uses exists and each link answers. LinkedIn and Amazon refuse scripted requests, so their links aren't checked. It runs on every pull request that touches the profile and every Monday, when it also opens an issue if the date of `llms-full.txt` is later than the one in the profile. GitHub turns off scheduled workflows after 60 days without activity in a repository: if that happens, turn it back on in the Actions tab.

## Images

Each image has a light and a dark version, and the profile picks the one that matches the reader's GitHub theme with `<picture>`. The images are SVG files with their text kept as text and the site's fonts (Inter and Newsreader, under the SIL Open Font License) embedded, so a label can be changed in any text editor. After a change, check both versions on github.com in light and dark mode, and on a phone.
