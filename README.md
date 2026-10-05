# SDR-Access

Receptor de rádio definido por software (SDR) totalmente acessível por voz, otimizado e testado com o [NVDA](https://www.nvaccess.org/) e também com outros leitores de tela. O programa tem integração direta com NVDA, JAWS e System Access e é compatível com qualquer leitor de telas: os controles são nativos do Windows e, se nenhum desses leitores estiver em execução, as falas do programa saem pelo sintetizador de voz padrão do Windows.

Suporta recepção via dongle RTL-SDR local (USB), ou remota via servidor **SpyServer** ou **RTL-TCP** pela rede — e também pode funcionar como servidor, compartilhando o seu dongle com outro SDR-Access (Modo Servidor), com busca de dongles na rede local, de servidores SpyServer públicos e histórico de servidores. Demodula AM, FM, WFM, NFM, banda lateral (LSB/USB) e CW, com squelch, controle de ganho, filtros, notch, varredura de VFO/memórias/automática, decodificadores digitais experimentais (RDS, CTCSS, MDC-1200/FleetSync, APRS, ACARS, Morse/CW e modos de voz digital via dsdcc), gravação do áudio recebido em WAV, MP3 ou FLAC (inclusive gravação por atividade) e controle CAT de transceptores externos via Hamlib.

## Download

Baixe a versão mais recente na aba **[Releases](../../releases)** deste repositório. O pacote já vem pronto pra rodar no Windows — não precisa instalar Python nem compilar nada. O manual completo em PDF acompanha cada Release.

Cada Release traz as notas da versão com o hash **SHA-256** de cada arquivo. Só são oficiais os arquivos publicados ali — cópias obtidas por qualquer outro canal não têm garantia de integridade.

## Requisitos

- Windows 10/11 (64 bits)
- Um dongle RTL-SDR (USB), **ou** acesso a um servidor SpyServer/RTL-TCP na rede
- Um leitor de tela é opcional, mas recomendado ([NVDA](https://www.nvaccess.org/), JAWS, System Access ou outro) — sem ele, o programa fala pelo sintetizador de voz padrão do Windows

## Driver do dongle RTL-SDR

Se o Windows não reconhecer o dongle corretamente pro programa (uso local via USB), baixe também o **instalador de driver** disponível na mesma página de Releases e rode como administrador.

## Licença

Veja [LICENSE](LICENSE). Este programa usa bibliotecas de terceiros — as licenças de cada uma estão detalhadas lá.
