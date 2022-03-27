# Finhub test task

Tech used :
- Go 1.17.6
- Gorm (https://github.com/go-gorm/gorm) as ORM library 
- Fiber (https://github.com/gofiber/fiber)
- Testify (https://github.com/stretchr/testify)

How to start :

- Run db with docker-compose up --build
- Build go app with go build -o app
- Send request to http://localhost:3000/slowest-queries/:page/size/:pagesize/type/:query-type(SELECT,INSERT...)
