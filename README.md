# Coding Best Practices

This repository is a personal compilation of coding best practices I learned or not, the easy or the hard way, along my journey as a software engineer.

## Formatting

1. The golden rule is that new is always better, no need to stick to the existing text formatting
1. In comments and other forms of documentation, infinitive form ( _e.g._ "add" ), third-person singular simple present ( _e.g._ "adds" ), present participle ( _e.g._ "adding" ) and simple past ( _e.g._ "added" ) can be mixed up
1. `"` and `'` are the same things, one can use them interchangeably in the same file
1. `"        "` and `"	"` are the same things, one can also use them interchangeably in the same file

## Maintenance

1. If it works, don't touch it
1. If it works now, it will work with 100 times more load
1. This is a temporary solution
1. TODO: fix it later

## Ownership

1. You touch it, you own it
1. Deletion Driven Development, also known as Scream Driven Development, consists in a nutshell in deleting this unknown and apparently-unused piece of software/infrastructure and transferring ownership to the first person to complain

## Versioning

1. After introduction a breaking change, add a description in the breaking-change section of the changelog, and only bump the [semver](https://semver.org/) PATCH version

## Workflows

1. Monorepo just works
1. Multirepo just works

## Disclaimer

Obviously, everything described in here is purely ironic. These pro-tips should not be used in real life for the sake of readability, maintainability and scalability.

## License

Unless explicitly stated to the contrary, all contents licensed under the [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/).
