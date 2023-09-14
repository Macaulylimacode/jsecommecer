# E-COMMERCER

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Macaulylimacode/jsecommecer/blob/master/LICENSE) 


![Captura de tela 2023-09-02 215404](https://github.com/Macaulylimacode/jsecommecer/assets/139823222/c3481c64-8533-4830-b052-737819ab704b)


# Informações do Projeto:
### Project Information:

Projeto de um e-commercer, onde vai encontrar dentro do mesmo as seguintes coisas.
° filtro de masculino e feminino além 
° Carrinho de compra
° Finalização
° histórico de Compras
O e-commerce funciona como uma loja virtual e representa um excelente canal de venda online para as empresas.
Na prática, significa que o lojista pode comercializar os seus produtos por meio de um site exclusivo e personalizado e,
se preferir, centralizar ali as suas operações.

Project of an e-commercer, where you will find the following things within it.
° male and female filter in addition
° shopping cart
° Finalization
° purchase history
E-commerce works like a virtual store and represents an excellent online sales channel for companies.
In practice, it means that the shopkeeper can market his products through an exclusive and personalized website and,
if you prefer, centralize your operations there.

```bash
Visualização da página acesse a parte
de ações/ actions para ter acesso ao prejeto.
```



# Preview do projeto:
### Project preview:

![Captura de tela 2023-09-02 215311](https://github.com/Macaulylimacode/jsecommecer/assets/139823222/1d541f98-d822-401a-b9c8-6fd727110c73)

![Captura de tela 2023-09-02 215250](https://github.com/Macaulylimacode/jsecommecer/assets/139823222/848b128a-3571-40ec-b9e7-12cfe55b940a)

![Captura de tela 2023-09-02 215329](https://github.com/Macaulylimacode/jsecommecer/assets/139823222/5ef7b663-f350-40ba-8b3f-f75f5c2c2279)

![Captura de tela 2023-09-02 215420](https://github.com/Macaulylimacode/jsecommecer/assets/139823222/47245a97-f769-4f28-9209-fed2c445f70d)

![Captura de tela 2023-09-02 215509](https://github.com/Macaulylimacode/jsecommecer/assets/139823222/d441b946-0a46-4750-acde-6a80f68dbce0)




# Tecnologias utilizadas:
### Technologies used:

![java](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)

![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)

## Trechos do Código:
### code snippets:

```bash
import { catalogo, salvarLocalStorage, lerLocalStorage } from "./utilidades";

const idsProdutoCarrinhoComQuantidade = lerLocalStorage("carrinho") ?? {};

function abrirCarrinho() {
  document.getElementById("carrinho").classList.add("right-[0px]");
  document.getElementById("carrinho").classList.remove("right-[-360px]");
}

function fecharCarrinho() {
  document.getElementById("carrinho").classList.remove("right-[0px]");
  document.getElementById("carrinho").classList.add("right-[-360px]");
```

```bash
import tailwindcss from "tailwindcss";
import { resolve } from "path";
import { defineConfig } from "vite";

export default defineConfig({
  base: "/jsecommecer/",
  plugins: [],
  resolve: {
    /*something*/
  },
  css: {
    postcss: {
      plugins: [tailwindcss],
    },
  },
  build: {
    rollupOptions: {
      input: {
        main: resolve(__dirname, "./index.html"),
        checkout: resolve(__dirname, "./checkout.html"),
        pedidos: resolve(__dirname, "./pedidos.html"),
      },
    },
  },
});

```

## IDE

![pycharm](https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white)
![visual](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white)

# Como executar o projeto

```bash
# clonar repositório
git clone https://github.com/Macaulylimacode/jsecommecer

# entrar na pasta do projeto
cd jsecommecer

# executar o projeto
./mvnw spring-boot:run
```

# Autor

Macauly lima

[![linkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/macauly-lima-75984a269)
