# Blog App

## Description

> The **Blog app** is a classic blog and a fully functional website that shows the list of posts and empower readers to interact with them by adding comments and liking posts.

## Built With

- Ruby

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

> You need the following tools be installed in your computer:
>
> - [Git](https://www.linode.com/docs/guides/how-to-install-git-on-linux-mac-and-windows/)
> - [Ruby](https://github.com/microverseinc/curriculum-ruby/blob/main/simple-ruby/articles/ruby_installation_instructions.md)
> - [Rails](https://www.tutorialspoint.com/ruby-on-rails/rails-installation.htm)

### Setup

1. Download the `Zip` file or **Clone the repo with**:

```bash
git clone https://github.com/tresorsawasawa/blog_app.git
```

2. To access the project directory

```bash
cd blog_app
```

### Install the app

```bash
bundle install
rails db:migrate
```

### Run the seeder

```
rails db:seed
```

### Run the App

```bash
rails s
```

```
Check http://localhost:3000/ in your browser
```

### Run Test

- To run models tests
```bash
rspec spec/models
```
- To run views tests
```bash
bundle exec rspec spec/views
```

## Author

👤 **Trésor Sawasawa**

- GitHub: [@tresorsawasawa](https://github.com/tresorsawasawa)
- Twitter: [@tresorsawasawa](https://twitter.com/TresorSawasawa)
- LinkedIn: [Trésor Sawasawa](https://www.linkedin.com/in/tresor-sawasawa/)

👤 **Kandi Peter**

- GitHub: [Kandi-Peter](https://github.com/Kandy-Peter)
- LinkedIn: [Kandi-Kamuntu](https://www.linkedin.com/in/kandi-peter-a49590212/)
- twitter: [Kandi_Peter](https://twitter.com/peter_kandy)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/tresorsawasawa/blog_app/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgements

- A great thanks to my coding partners, morning session team, and standup team partners for their contribution.
- [Microverse](https://www.microverse.org/)

## 📝 License

This project is [MIT](./MIT.md) licensed.
