### 1. Acessar o Prompt de Comando
* Pressione Win + R para abrir a janela "Executar".
* Digite cmd e pressione Enter.
### 2. Executar os comandos
  ##### a) Limpar o cache DNS No Prompt de Comando, digite:

```
ipconfig /flushdns
```
  Isso limpa o cache DNS, útil para atualizar as informações de resolução de nomes.
  
  ##### b) Liberar o endereço IP atual
  
* Para liberar o endereço IP atribuído ao seu adaptador de rede, digite:

```
ipconfig /release
```

Esse comando desativa a conexão de rede temporariamente ao liberar o IP.

  ##### c) Solicitar um novo endereço IP
* Para solicitar um novo IP do servidor DHCP, digite:
```
ipconfig /renew
```
O sistema vai tentar obter um novo endereço IP e restaurar a conectividade.


#### Esses comandos podem ajudar a solucionar problemas de conexão e atualização de IP. Se não houver problemas, a conexão deve ser restaurada após ipconfig /renew.
