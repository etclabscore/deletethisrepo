# Contribute

This project is open source project provided by ETC Labs Core and contributions are welcomed by everyone. Anyone can contribute improvements, fixes, and even entirely new topic feature in the navigation.

## Prerequisite 

- [Pristine](https://github.com/etclabscore/pristine) is an open standard for documentation driven development. Pristine helps drive high quality community development.
  - https://github.com/etclabscore/pristine/blob/master/CONTRIBUTING.md
  - https://github.com/etclabscore/pristine/blob/master/CONVENTIONAL_COMMITS.md 

### Getting Started

- Fork the repository.
- Make changes in your fork of the repository.
- Submit a pull request.

### Tips n Tricks

__Create a new topic.__
- create a new Markdown document `_NEWTOPIC.md`
- save the Markdown document in `source/includes/`
  
```
.
├── _NEWTOPIC.md
└── _contribute.md
```
- Include the new document in `/index.html.md`
  
```shell
includes:
  - contribute
  - NEWTOPIC
```
