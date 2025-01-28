# Hora do Sistema

Este é um programa em Java que exibe a data e hora atual do sistema. O programa utiliza a classe `Date` para obter essas informações e as imprime no console.

---

## Tabela de Conteúdos

1. [Descrição](#descrição)  
2. [Código](#código)  
3. [Como Funciona](#como-funciona)  
4. [Como Executar](#como-executar)  
5. [Exemplo de Execução](#exemplo-de-execução)  
6. [Tecnologias Utilizadas](#tecnologias-utilizadas)  
7. [Contribuições](#contribuições)  
8. [Licença](#licença)  

---

## Descrição

Este projeto é uma introdução simples ao uso da classe `Date` em Java para obter a data e hora atual do sistema e exibi-las no console.

---

## Código

Abaixo está o código do programa:

```java
import java.util.Date;

public class HoraDoSistema {
    public static void main(String[] args) {
        Date relogio = new Date();
        System.out.println("A hora do Sistema é");
        System.out.println(relogio.toString());
    }
}
```

---

## Como Funciona

1. O programa cria uma instância da classe Date, que representa os dados e a hora atual do sistema no momento de sua criação.
2.  A hora do sistema é exibida no console por meio do método toString()da classe Date.

---

## Como Executar

Pré-requisitos

- Certifique-se de que o Java Development Kit (JDK) esteja instalado em sua máquina.
- Um terminal ou IDE que suporta Java.

Passos para executar:

1 - Clone ou faça o download do repositório:

```java
git clone https://github.com/seu-usuario/hora-do-sistema.git
cd hora-do-sistema
```
2 - Compilar o programa:

```java
javac HoraDoSistema.java
```
3 - Execute o programa:

```java
java HoraDoSistema
```

---

## Exemplo de Execução

Saída esperada no console:

```java
A hora do Sistema é
Fri Jan 24 10:35:28 BRT 2025
```
Nota: Os dados e horários exibidos serão diferentes, pois são baseados na hora atual do sistema no momento da execução.

---

## Tecnologias Utilizadas

- Linguagem: Java
- Biblioteca: java.util.Date

---

## Licença

Este projeto está licenciado sob a MIT License.


