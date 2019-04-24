# Project history
프로젝트 진행 내용

## Single Chat
1. client : PowerShell에서 npx 명령어로 프로젝트 구성  
  ![chat client initialize](./img/img_initialize.png)
  
2. client : install socket.io-client
    ```
    npm install socket.io-client 
    ```
3. client : Add single chat page 
4. client : Change server host/port
    ```
    server: {
        port: 8080, // default: 3000
        host: '0.0.0.0' // default: localhost
    }
    ```
5. client : single chat socket 연동 코드 작성
6. server : server side 프로젝트 구성
    ```
    // install express-generator globally
    npm install express-generator -g
    
    // let's use express generator to set up
    express server
    ```
7. server : install socket.io with --save option.
    ```
    npm install socket.io --save
    ```
8. server : add sending and getting data module 


