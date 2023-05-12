go mod init github.com / 1bhavyasingh1 / go - react




go get - u github.com / gofiber / fiber / v2





npm create vite client -- --template react-ts







package main

import "fmt"

func main(){
	fmt.Print("Hello World")
}










package main

import {
	"fmt"

	"github.com/gofiber/fiber"

}

func main(){
	fmt.Print("Hello World")

	app:= fiber.New()
}






app.Get("/healthcheck", func(c *fiber.Ctx) error {
		return c.SendString("Ok")
	}) //func is a callback function