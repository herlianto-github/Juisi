## Juisi
An Awesome Healthy App Assistant Right from your fridge

## Getting Started

### Dependencies

- [Git](https://git-scm.com)
- [Golang](https://go.dev)
- [Visual Studio Code](https://code.visualstudio.com)

### How To Contribute

- Fork this repository

    ```console
    $ git clone https://github.com/YOUR_USERNAME/Juisi.git
    > Cloning into `Juisi`...
    > remote: Counting objects: 10, done.
    > remote: Compressing objects: 100% (8/8), done.
    > remove: Total 10 (delta 1), reused 10 (delta 1)
    > Unpacking objects: 100% (10/10), done.
    ```
    
    ```console
    cd Juisi
    ``` 
    
- Simple run  

    ```console
    go mod init juisi
    ```

    ```console
    touch main.go    
    ```

    ```console
    echo 'package main 
    
    import "fmt"
    
    func main(){
    
        fmt.Println("Hello World")
    
    }' >> main.go
    ```
    
    ```console
    go run main.go
    ```

- Important

    ```console
    git checkout -b feature-name 
    ```
    Always create new branch when develop something

    ```console
    git add .    
    ```
    
    ```console
    git commit -m "feature description"
    ```
    
    ```console
    $ git remote -v
    > origin  https://github.com/YOUR_USERNAME/Juisi.git (fetch)
    > origin  https://github.com/YOUR_USERNAME/Juisi.git (push)
    ```
    
    ```console
    $ git remote add upstream https://github.com/herlianto-github/Juisi.git
    ```
    
    ```console
    $ git remote -v
    > origin    https://github.com/YOUR_USERNAME/Juisi.git (fetch)
    > origin    https://github.com/YOUR_USERNAME/Juisi.git (push)
    > upstream  https://github.com/herlianto-github/Juisi.git (fetch)
    > upstream  https://github.com/herlianto-github/Juisi.git (push)
    ```
    
    ```console
    git push -u origin feature-name    
    ```

### Executing program

- How to run the program

    ```console
    go run main.go    
    ```

## Help

- **Configs**<br/>Contain database and http configuration
- **Delivery (API)**<br/>API http handlers or controllers
- **Entities**<br/>Contain database model
- **Repository** <br/> Contain implementation entities database anq query with ORM.
- **Utils**<br/>Contain database driver (mySQL)

## Authors

[Herlianto](https://github.com/herlianto-github)

## Version History

- 0.0.1
  - Initial Release

## Acknowledgments

- [Layered Architecture](https://www.oreilly.com/library/view/software-architecture-patterns/9781491971437/ch01.html)
