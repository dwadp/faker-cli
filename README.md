
# Faker CLI

A simple CLI application for generating fake data. This application is just for learning purposes.

## Install
Run the following command in your terminal:
```
go get github.com/dwadp/faker-cli
```

## Usage
Example #1: _Simple generate command_
```
faker-cli gen --fields name,email,phone --times=50
```

Example #2: _Generate and save to a file_
```
faker-cli gen --fields name,email,phone --save-to=/path/to/generate/file.json
```

> 📘 _This library only support saving into a `json` file._

---

## 🧾 Libraries Used
- Cobra [https://github.com/spf13/cobra](https://github.com/spf13/cobra)
- Faker [https://github.com/bxcodec/faker](https://github.com/bxcodec/faker)