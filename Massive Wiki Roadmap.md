# Massive Wiki Roadmap

## Improving Massive Wiki Builder

### Now

- [x] [[MWB3]] - replace Markdown parser with [[Mistletoe]]
- [ ] port alpha + chrono All Pages from developer wiki's this themes / Basso and make a MWT release
	- [ ] some day make alpha + chrono divs into tabs, use [jQuery tabs](https://jqueryui.com/tabs/) to toggle
- [ ] pass build-results dict to page rendering, add build-results section in Basso (maybe commented out?)
- [x] [Format incipient links differently #37](https://github.com/peterkaminski/massivewikibuilder/issues/37)
- [x] backlinks (in a right-hand sidebar? at the bottom of the page? like TiddlyWiki?)

### Up Next

- [ ] annotate external links with destination domain (e.g., `[Iron](https://en.wikipedia.org/wiki/Iron)` gets " (en.wikipedia)" appended)
- [ ] password-protect deployed with with StatiCrypt or PageCrypt
- [ ] merge all calls to .render() into one call #refactoring
- [ ] separate home page template (generalize to _many_ page templates)
- [ ] more than one sidebar (left, right)
- [ ] decide whether we want a plugin system or not
- [ ] <https://github.com/peterkaminski/massivewikibuilder/issues>
- [ ] look at [Stork](https://stork-search.net/) for another search engine (in addition or to supplant [[Lunr]])
- [ ] continue to evaluate other [[Python Markdown engines]]

## Massive Wiki Projects

- [ ] improving Massive Wiki Builder
	- [ ] mwb3 (ready to ship 3.1)!
	- [ ] finish Coriander theme
- [ ] create [[Opal]]
- [ ] create [[Zircon]]
	- [ ] kill or revive [Missive Weaver](https://github.com/peterkaminski/missive-weaver)
- [ ] create [[Pier2Pier]]
	- [ ] may be obviated by [[Obsidian Git]]'s source control view
- [ ] announce MWB in Obsidian Forum and where people talk about Obsidian+Hugo

## Icebox / Looking to the Future

- [ ] move MWB and MWT central repos from github:peterkaminski to github:Massive-Wiki
- [ ] store Massive Wiki on Hyperdrive?
- [ ] store Massive Wiki as [Noosphere](https://subconscious.substack.com/p/noosphere-a-protocol-for-thought) spheres?
- [ ] publish Massive Wikis vis [Distributed Press](https://distributed.press/)?
- [ ] other filesystems / messaging systems: IPFS, Nostr

## Blog About Our Experiences

- [ ] version control and sharing: Pijul, Syncthing, Git, Git forges
- [ ] use SuperLiminal
- [ ] Wiki Culture

Wow, I am *so* glad to see the edit button in a/the reference MassiveWiki. It's a hack, no question, but it works! Also, looking forward to the blogging. Where is the blog? --JohnAbbe
