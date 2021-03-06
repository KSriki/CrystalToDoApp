# TodoApp

Basic Todo App using Crystal/Kemal

## Installation

TODO: Write installation instructions here

## Usage

TODO: Write usage instructions here

## Development

### DB Mockup

Users have many Notes

- Users
    - username
    - password
    - age
    - City of Origin
    - email
- Notes
    - Title
    - Content
    - Date
    - Edited On
    - user_id (fk)

### Tech/framework used

Kemal Web Application:

<b>Built with</b>
- [React](https://reactjs.org/)
- [Kemal - Crystal](https://kemalcr.com/guide/)
    - [Shards Dependency Manager](https://github.com/crystal-lang/shards)
    - [Kilt - Generic template interface for Crystal](https://github.com/jeromegn/kilt)
- [Semantic UI](https://react.semantic-ui.com/)
- [Crystal-PG Postgres driver](https://github.com/will/crystal-pg)
- [jennifer ORM based on ActiveRecord](https://github.com/imdrasil/jennifer.cr) 
    - [Sam.cr Rake/Make-like task manager](https://github.com/imdrasil/sam.cr)
    - [Internationalization API ( i18n )](https://github.com/TechMagister/i18n.cr)
        - Internationalization is the process of designing a software application so that it can be adapted to various languages and regions without engineering changes. 


Possibility: Amber (web app framework for crystal) with Granite ORM. Kind of like Rails.

### Jennifer
Jennifer setup guide: https://github.com/imdrasil/jennifer.cr/blob/master/docs/getting_started.md

```bash
crystal sam.cr -- help
```

### Features to be implemented

- CRUD Notes
- CRUD Users

## Contributing

1. Fork it (<https://github.com/KSriki/CrystalTodoApp/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [Srikant Kumar Kalaputapu](https://github.com/KSriki) - creator and maintainer
