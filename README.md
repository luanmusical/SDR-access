# SDR-Access

Receptor de rádio definido por software (SDR) totalmente acessível por voz, integrado ao [NVDA](https://www.nvaccess.org/) (com repique automático no sintetizador padrão do Windows caso o NVDA não esteja rodando).

Suporta recepção via dongle RTL-SDR local (USB), ou remota via servidor **SpyServer** ou **RTL-TCP** pela rede. Demodula AM, FM, WFM, NFM, banda lateral (LSB/USB) e CW, com squelch, controle de ganho, filtros, notch, varredura de VFO/memórias/automática, e decodificadores digitais experimentais (RDS, CTCSS, MDC-1200/FleetSync, APRS, ACARS, Morse/CW e modos de voz digital via dsdcc).

## Download

Baixe a versão mais recente na aba **[Releases](../../releases)** deste repositório. O pacote já vem pronto pra rodar no Windows — não precisa instalar Python nem compilar nada.

Cada Release traz as notas da versão com o hash **SHA-256** de cada arquivo. Só são oficiais os arquivos publicados ali — cópias obtidas por qualquer outro canal não têm garantia de integridade.

## Requisitos

- Windows 10/11 (64 bits)
- Um dongle RTL-SDR (USB), **ou** acesso a um servidor SpyServer/RTL-TCP na rede
- [NVDA](https://www.nvaccess.org/) instalado (opcional — sem ele, o programa fala pelo sintetizador de voz padrão do Windows)

## Driver do dongle RTL-SDR

Se o Windows não reconhecer o dongle corretamente pro programa (uso local via USB), baixe também o **instalador de driver** disponível na mesma página de Releases e rode como administrador.

## Licença

Veja [LICENSE](LICENSE). Este programa usa bibliotecas de terceiros — as licenças de cada uma estão detalhadas lá.
