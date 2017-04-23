# Integração Pagseguro - Wordpress

## Objetivo
Este repositório tem o objetivo de integrar seu site no Wordpress com o [PagSeguro](https://pagseguro.uol.com.br/), para que sejam feitos pagamentos na plataforma deles e, ao mesmo tempo, seja possível que o comprador verifique seu status de pagamento.

O ponto diferencial deste projeto é a simplicidade e o passo a passo. Existem alguns repositórios sobre o tema, inclusive o oficial, que falam sobre o tema, mas são muito desorganizados, fazendo com que quem está iniciando não entenda como fazer o processo. Digo isso por experiência própria.

## Progresso
O desenvolvimento deste projeto será feito através de PHP, principalmente, que será usado para acessar a API do [PagSeguro](https://pagseguro.uol.com.br/). Será exibido o status de pagamento ao usuário após o fornecimento do código de pagamento que o comprador recebe por e-mail ao finalizar a compra:

![](https://github.com/andreszlima/phPagseguro/blob/master/C%C3%B3digo.png)

## Garanto que será possível criar um site em Wordpress com integração com PagSeguro.
## Passos a serem seguidos:
1. Organizar o PagSeguro para que receba seus pagamentos;

2. Adicionar botão para compra com PagSeguro ao seu site; (A partir desse ponto você já pode receber pagamentos em sua conta através do PagSeguro!

3. Obter token para consulta de status de pagamento;

4. Integrar a pesquisa feita no item anterior ao seu site, fornecendo acesso ao comprador;

5. Adicionar captcha (proteção contra usos repetidos por bots)

# Licença

[GNU General Public License v3.0](https://github.com/andreszlima/phPagseguro/blob/master/LICENSE.txt)
