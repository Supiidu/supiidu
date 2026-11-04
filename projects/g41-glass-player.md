# G41 Glass Player

> Projeto pessoal em desenvolvimento. Este documento é um estudo de caso técnico; o código-fonte ainda não foi publicado neste perfil.

## Visão geral

O **G41 Glass Player** é um projeto de personalização da experiência de reprodução musical em um **Motorola Moto G41** reutilizado como *digital audio player* (DAP). A proposta é integrar uma interface de música à experiência do sistema Android, com uma visualização do áudio em formato de onda contínua.

## Tecnologias e áreas exploradas

- **Android e Java** — implementação do projeto e integração com componentes do sistema.
- **Xposed/LSPosed** — experimentação com hooks para personalizar a interface do Android.
- **SystemUI e tela de bloqueio** — interação com elementos de interface e controles de mídia.
- **Processamento de áudio** — captura de informações espectrais e visualização em tempo real com FFT.
- **Desenvolvimento e depuração no Linux** — build iterativo, ADB e análise de logs.

## Funcionalidades trabalhadas

- Interface personalizada para a experiência de reprodução musical.
- Visualização do áudio com **onda preenchida e contínua**, em vez de barras independentes.
- Cores dinâmicas associadas à arte do álbum.
- Integração e ajustes de comportamento na interface do sistema, incluindo tela de bloqueio.

## Desafios técnicos

A integração com o SystemUI exige lidar com componentes internos que podem mudar entre versões e ROMs. A evolução do projeto envolveu identificar pontos de integração, investigar falhas por `logcat` e iterar sobre comportamento e visualização do áudio.

## Estado da publicação

Este estudo de caso registra o escopo do trabalho, **não representa uma release pública nem um build reproduzível**. O projeto está em um ambiente local e deve ganhar um repositório próprio, com seu código original, histórico Git preservado, instruções de build e licença adequada, depois da revisão de arquivos e dependências.

> **Nota:** a visualização usa técnicas de processamento de sinais; ela não é, por si, um sistema de machine learning ou IA.
