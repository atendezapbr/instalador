# Instalador Whaticket

Substituimos a instalação do docker por um comando único para maior compatibilidade com as diferentes arquiteturas de servidores. 
i386, arm64, x86_64 / 64 Bits.

Modificamos para que o PostgreSQL seja instalado sem problemas em diferentes arquiteturas.

```bash
sudo apt -y update && apt -y upgrade
```

PASSO 1 - DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/atendezapbr/instalador.git instalador && sudo chmod -R 777 instalador  && cd instalador  && sudo ./install_primaria
```

PASSO 2 - DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS // COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:

```bash
cd instalador  && sudo ./install_instancia
```

## Requisitos

| --- | Mínimo | Recomendado |
| --- | --- | --- |
| Node JS | 20.x | 20.x |
| Ubuntu | 20.x | 20.x |
| Memória RAM | 4Gb | 8Gb |  
