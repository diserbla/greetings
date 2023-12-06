# Saludos en Go

Este paquete proporciona una forma simple de obtener saludos personalizados en Go.

## Instalación

Ejecuta el siguiente comando:

```bash
go get -u github.com/diserbla/greetings

ackage main

import (
	"fmt"
	"github.com/diserbla/greetings"
)

func main() {
	message := greetings.Hello("John")
	fmt.Println(message)
}

