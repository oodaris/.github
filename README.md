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

The profile names no customer. Then set the date in the comment at the end of `profile/README.md` to the "Last updated" date of [llms-full.txt](https://oodaris.ai/llms-full.txt).

The [Profile README](.github/workflows/profile-readme.yml) workflow checks, on every pull request that touches the profile, that each image exists and each link answers. Every Monday it runs the same checks and opens an issue if the site's content is newer than the profile.

## Images

Each image has a light and a dark version, and the profile picks the one that matches the reader's GitHub theme with `<picture>`. The images are SVG files with their text kept as text and the site's fonts (Inter and Newsreader, under the SIL Open Font License) embedded, so a label can be changed in any text editor. After a change, check both versions on github.com in light and dark mode, and on a phone.
