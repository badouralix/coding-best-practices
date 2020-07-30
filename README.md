# Coding Best Practices

This repository is a personal compilation of coding best practices I learned or not, the easy or the hard way, along my journey as a software engineer.

## Bugs

1. There are no bugs, only unintended features.

## Development

1. Just commit garbage without proofreading it, thanks to [github suggested changes](https://github.blog/changelog/2018-10-16-suggested-changes/) reviewers will take care of fixing it.
1. Friend Driven Development is the practice of approving your friends' pull requests without reading them. Obviously an implicit friendship agreement stipulates that one approval is worth another approval, so that the Friend Driven Development can keep going.
1. The previous point shall not be confused with the Genius Driven Developement, which consists in approving your teammates' pull requests without reading them because they are geniuses. The approval is merely here to by-pass the branch protection rules. Please refer to [the inner json effect](https://thedailywtf.com/articles/the-inner-json-effect) for more details on this best practice.

## Formatting

1. The golden rule is that new is always better, no need to stick to the existing text formatting.
1. In comments and other forms of documentation, infinitive form ( _e.g._ "add" ), third-person singular simple present ( _e.g._ "adds" ), present participle ( _e.g._ "adding" ) and simple past ( _e.g._ "added" ) can be mixed up.
1. `"` and `'` are the same things, one can use them interchangeably in the same file.
1. Spaces and tabs are the same things, one can also use them interchangeably in the same file.

## Maintenance

1. If it works, don't touch it.
1. If it works now, it will work with 100 times more load.
1. This is a temporary solution.
1. TODO: fix it later.

## Ownership

1. You touch it, you own it.
1. Deletion Driven Development, also known as Scream Driven Development, consists in a nutshell in deleting this unknown and apparently-unused piece of software/infrastructure and transferring ownership to the first person to complain.

## Reliability

1. Want to know if your change will break prod? Ship it. Prod is the best testing environment because it's the closest thing to prod.

## RFCs

1. RFCs are a waste of time. You want to know how people feel about something you want to do? Do it, and see who complains.
1. If you have no choice but to write an RFC, make sure it's imprecise enough so that no constructive criticism can be made.

## Versioning

1. After introducing a breaking change, add a description in the breaking-change section of the changelog, and only bump the [semver](https://semver.org/) PATCH version.

## Workflows

1. Monorepo just works.
1. Multirepo just works.

## Disclaimer

Obviously, everything described in here is purely ironic. These pro-tips should not be used in real life for the sake of readability, maintainability and scalability.

## License

Unless explicitly stated to the contrary, all contents licensed under the [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/).
