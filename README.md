# Clarence Predovic 🚀

Welcome to my GitHub profile! I'm a passionate software developer with a love for building scalable and efficient systems.

## About Me

I'm a seasoned developer with expertise in Rust, Node.js, GraphQL, and MongoDB. I enjoy contributing to open-source projects and collaborating with like-minded individuals to create innovative solutions.

## Skills

* **Rust**: My primary language of choice, with a focus on systems programming and performance-critical applications.
* **Node.js**: Experienced with building scalable and efficient server-side applications using Node.js.
* **GraphQL**: Skilled in designing and implementing GraphQL APIs for data-driven applications.
* **MongoDB**: Familiar with NoSQL databases and their applications in modern software development.

## Get in Touch

Feel free to reach out to me at clarence.clarence@yahoo.com or through my GitHub profile for any collaboration opportunities or just to say hi!

## My GitHub Actions

### test.yml

```yml
name: test

on:
  push:
    branches: [ main ]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
    - name: Checkout code
      uses: actions/checkout@v3
    - name: Test
      run: echo 'Success!'

```

