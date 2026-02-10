## 🧠 Questões Teóricas sobre DNS

**1.** O que significa a sigla DNS e qual é sua principal função?DNS significa Domain Name System (Sistema de Nomes de Domínio).
A principal função é traduzir nomes de domínio (ex: google.com) em endereços IP (ex: 142.250.219.78).

**2.** Por que o DNS foi criado? Qual problema ele resolveu na Internet?Foi criado para resolver o problema de ter que memorizar endereços IP numéricos.
Com o DNS, as pessoas usam nomes fáceis em vez de números difíceis.

**3.** O que é um nome de domínio? Dê um exemplo.É o nome legível que identifica um site na internet.
👉 Exemplo: www.youtube.com

**4.** Qual é a função de um servidor DNS?Responder consultas, informando qual endereço IP está associado a um nome de domínio.

**5.** Cite dois tipos de registros DNS e explique brevemente um deles.A – associa um domínio a um endereço IPv4

MX – define servidores de e-mail
👉 Exemplo explicado: o registro A aponta um site para seu IP.

---

## 🪟 Questões sobre DNS no Windows

**6.** Qual comando do Windows é utilizado para testar a resolução de nomes DNS?nslookup

**7.** Para que serve o comando `ipconfig /all` em relação ao DNS?Mostra servidores DNS configurados, nome do host e outras informações de rede.

**8.** Qual comando pode ser usado para limpar o cache DNS no Windows?ipconfig /flushdns

**9.** Onde o Windows armazena temporariamente as informações de DNS?No cache DNS do sistema, mantido em memória.

**10.** Ao acessar um site no Windows e ocorrer erro de DNS, cite uma possível causa.Servidor DNS inacessível ou configurado incorretamente.

---

## 🐧 Questões sobre DNS no Linux

**11.** Qual arquivo do Linux contém os servidores DNS configurados no sistema?/etc/resolv.conf

**12.** Qual comando pode ser usado no Linux para consultar registros DNS de um domínio?dig ou nslookup

**13.** Para que serve o comando `ping` em relação ao DNS?Testa se o nome do domínio está sendo resolvido para um IP e se o host responde.

**14.** Qual a função do arquivo `/etc/hosts` no processo de resolução de nomes?Faz resolução local de nomes, antes da consulta ao DNS.

**15.** Cite uma diferença básica entre a configuração de DNS no Windows e no Linux.Windows: configuração via interface gráfica ou ipconfig

Linux: configuração via arquivos de texto (ex: /etc/resolv.conf)

---
