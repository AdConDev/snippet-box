# SnippetBox

SnippetBox is a web application that allows users to create, store, and manage code snippets.

## Features

- User authentication and session management
- CRUD operations for code snippets
- Dynamic HTML templates for user interface
- Efficient request routing

## Getting Started

### Prerequisites

- Go
- MySQL

### Installation

1. Clone the repository
```sh
git clone https://github.com/consdotpy/snippetbox.git
```

2. Install dependencies
```sh
go mod download
```

3. Set up your MySQL database using the provided SQL scripts in the `sql/` directory. Be sure to change credentials in the `sql/create_user.sql` script before running it.

```sh
sudo mysql
source sql/*.sql
```


## Usage

Check `.env.example` for environment variables that need to be set. Then, run the application using `Makefile`:

```sh
make run
```

## Testing

To run quality control checks, execute:

```sh
make audit
```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## License

Distributed under the MIT License. See `LICENSE` for more information.