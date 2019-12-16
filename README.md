# Outline
# 1. Quick start
  1.1  Running environment
       only linux is supported curretly、node（12.13.1）、python3

  1.2  Creat images
      ```sh
       docker build -t mdHbuilder:1.0 .
       ```
  
  1.3  show docker images
      ```sh
      docker images
       ```
  1.4  run the image
  ```sh
  docker run --name mdHbuilder:1.0  -p  mdHbuilder:1.0
  ```
# 2. Project description 
## 2.1 Requirements
 only linux is supported curretly、node（12.13.1）、python3

## 2.2 Build
```sh
nvm install 12.3.1
sudo apt install python3
```

# 3. Docker
## 3.1 What is mdbuilder?
The main implementation of this project is to display multiple or single markdown files in web pages

## 3.2 How to use this image?
```sh
docker run -it --rm ...
```

## 3.2 Envrioments Var
 only linux is supported curretly
 ```sh
 Build node:12.13-alpine
 apk add python3
 ```

## 3.3 I/O
   import: Markdown folder path
   output: Page static file corresponding to output


## Build Setup

```sh
# nvm install or npm install

nvm install 12.3.1

# install dependencies
sudo apt install python3

# run it

python3 app.py input output
```