---
title: Anotaí — Política de privacidade
---

# Anotaí — Política de privacidade

**Última atualização:** 5 de novembro de 2026 (versão 3; a versão anterior é de 24 de setembro de 2026).
**Vale para:** o aplicativo Anotaí (Android), versão de captura por voz, sem conta de usuário e
sem serviço de nuvem próprio.

## O que o app faz por padrão, sem nenhuma configuração

Grava sua voz só quando você toca em gravar, transcreve no próprio aparelho, e guarda o áudio e o
texto como arquivos comuns, na pasta do app ou na pasta que você escolher no seu aparelho. **Nada disso
sai do seu aparelho.**

Enquanto você grava, o app pode mostrar um rascunho ao vivo do que você está dizendo. Esse rascunho vem
do reconhecedor de voz **do próprio Android, rodando dentro do aparelho**; se o seu aparelho não tiver o
reconhecimento no aparelho, o rascunho simplesmente fica desligado. O app nunca usa o reconhecimento de
voz em nuvem para isso.

Enquanto grava ou transcreve, o app mostra uma notificação ("gravando", "transcrevendo 40 %") para que o
Android não interrompa o trabalho quando a tela bloqueia. É só isso que a notificação faz.

## O que você pode ligar, sempre por sua escolha explícita

- **Mandar notas para o seu próprio computador**, via um endereço e uma chave que você mesmo cria ao
  ligar o programa FalAÍ (ou o MrNiceGraph) na sua máquina. Isto não é um servidor nosso: é um programa
  que roda no computador que é seu, e que você controla o tempo todo. O app manda o áudio e o texto para
  lá, e o computador pode devolver um texto melhor transcrito, com ligações entre as notas. Dentro da sua
  rede de casa a ligação é direta; fora de casa, só por um túnel criptografado (HTTPS) que você mesmo abre no
  seu computador. O app recusa qualquer endereço sem criptografia que não seja da sua rede local. Nada disso
  passa por nós.
- **Guardar as notas numa pasta do aparelho** que você escolhe pelo seletor do Android. Se essa pasta for
  sincronizada por outro app (Syncthing, Drive, o que você usar), quem leva os arquivos pela nuvem é esse
  app, sob a política dele.
- **Uma prancheta**, que troca pequenos textos e imagens entre o celular e esse mesmo computador
  seu, para você colar de um lado o que copiou do outro. Ela apaga sozinha em até 24 horas, e nada
  dela vira nota sem você tocar em "virar nota".
- **Recortar uma página que você compartilhar com o app** (um "clipar de site"): o endereço que
  você compartilhou é enviado ao seu computador, que busca aquela página pública e extrai o texto
  legível dela para virar uma nota. Só a página que você escolheu é buscada — nunca outra.
- **"Compartilhar com" o Anotaí**: um áudio, um texto ou um link que você mandar de outro app (o
  WhatsApp, por exemplo) vira uma nota no seu aparelho. O áudio fica guardado no formato original; se
  ele não for do tipo que o celular transcreve sozinho, a transcrição é feita pelo seu computador, se você
  o tiver ligado, ou não é feita.

**Transcrição em nuvem não faz parte desta versão.** O Anotaí distribuído pelo Google Play transcreve só no
aparelho ou, se você ligar, no seu próprio computador. Ele não envia o seu áudio a nenhum serviço de
transcrição de terceiros.

## O que nós — os autores do app — nunca vemos, coletamos, vendemos nem compartilhamos

**Nada.** Não existe conta, não existe login, não existe servidor nosso recebendo seus dados, não existe
anúncio, análise de uso nem relatório de falhas enviado a ninguém. Tudo o que este app faz com informação
sua acontece entre o seu aparelho e, quando você escolhe ligar, o seu próprio computador. A única ligação à
internet que o app faz por conta própria é baixar, quando você pede, o modelo de transcrição que roda no
aparelho.

## Como apagar tudo

No app, arquivar tira a nota da lista, mas ela continua guardada no aparelho. Para apagar tudo, limpe os
dados do app (Configurações do Android › Apps › Anotaí › Armazenamento) ou desinstale o app. Se você usou a
pasta do aparelho, apague os arquivos dela. Se você usou o computador, os dados guardados lá seguem as mesmas
regras do programa que você instalou: no FalAÍ, apagando a pasta de notas e revogando o aparelho; no
MrNiceGraph, pelo terminal, `mrn prancheta <pasta> --apagar-tudo` limpa a prancheta.

## Contato

varelladados@gmail.com
