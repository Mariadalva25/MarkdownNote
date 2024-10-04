# Blockchain
    É uma cadeia de blocos. Cada bloco tem uma série de dados, esses dados podem ser respeito sobre transações, mas também podem ser imagens, filmes, música ou texto em geral. Cada bloco contem informações sobre o bloco anterior conectados entre si.

# Propriedades
  Uma das propriedades importantes é que se alteramos um dado,uma letra que seja dentro de um bloco, A blockchain inteira é alterada. Isso funciona graça a função Hash.
  Basicamente uma função hash irá pegar um texto de entrada(input) e vai gerar um texto de saída (output).

  ## Propriedade da função hash
  * Fácil de computar
  * Livro de colisão* impossível 2 inputs  com o mesmo output
  * Unidirecional* impossível descobrir o input dado seu hash.
* "Puzze freiendly"(Amagavél com quebra-cabeça) Se fazermos uma modificação pequena no meu texto
  de entrada, o texto de saída vai ser modificado bastante.
   # Assinaturas Digitais
   São formas autenticar documentos virtualmente.
 ### caracterísiticas desejadas
* só você pode assinar
* Qualquer um pode verificar sua assinatura
  
# O Bitcoin
A rede bitcoin:
* O "banco central" da centralcoin é substituído por uma rde de computadores.
* Distribuída
* Sem hierarquia
* protocolo de consenso
  Não existe nenhum computador central.
Esse computadores precisam entrar em acordo. Nesse caso temos milhares de computadores.
## Como funciona?
Qualquer pessoa pode participar para isto você tem que baixar um bitclead(um conjunto de informações).
  > Dois tipos de nós nas redes Bitcoin
* Full nodes(nós completos)
  
- [ ] Validam todas as transações emitidas pela rede.
- [ ]  Mantêm a consistência da blockchain.
 
 >  Ligth nodes: (nós leves)
 - [ ] Não armazena todas a blockchain.
 - [ ] Necessitam de informações de outros nós.
  
  # Protocolo de concenso
  (Mineradores vão receber as transações e verifacam se está ok).
  * Validam as transações recebidas e criam novos blocos.
  * Competem entre si pelo direito de adicionar o próximo bloco na blockchain,
  * Verificam blocos obtidos por outros mineradores e adicionam s blockchain quando valida.
  * Sempre extendem o ramo mais longo da blockchain.
  As transações de bitcoin só se tornam efetivas quando são inseridas na blockchain e a mineração garante que todos os nós mantenham a mesma blockchain armazenada.
  # Proof of work
  Prova de trabalho é um algoritmo de concenso e o mais comum, usando principalmente para blockchain bitcoin.
    
O algoritmo garante que o primeiro minerador que apresentar a "prova de trabalho" de um bloco tenha a oportunidade de validá-lo.

O nonce é um valor númerico sem significado que é adicionado a cada blockchain. O mineradores alteram o valor tentam cumprim com requisitos do proof
# Bitcoin na prática
## O que significa ter bitcoins?
Basicamente que o banco promete para você que na hora que precisar  irá lhe devolver o seu dinheiro. No bitcoin você não tem uma conta ou saldo, o que você tem são moedas que foram criadas e que apontam uma chave pública que você controla.
Significa que moedas foram criadas endereçadas a sua chave pública e você ainda não usou essas moedas.
  A chave secreta é o que te dá a possibilidade de gastar as moedas que estão apontando para aquela chave e serve para assinar.
  Então basicamente ter bitcoin significa saber uma chave seccreta que seja associada uma chave pública.
  # Carteiras(Wallets)
  Sâo software que vão te ajudar a guardar a sua chave secreta e realizar transações usando bitcoin.



