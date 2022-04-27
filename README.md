# n0s
Tool to jailbreak Sagemcom F@ST 5657GF aka NOS Giga Router Wifi 6 and other compatible devices

### Features
- Fully disables TR-69 protocol (what allows the ISP to snoop into the device)
- Opens root access through telnet
- It disables ISP default accounts
- It enables advanced mode for XMO
- It changes critical passwords to random ones
- It disables the syslog server, better stability / no overspace usage

### !IMPORTANT!:
!!!! The router needs to have the default config applied, or at least the default credentials (admin/admin)
```
Utilização: n0s <opções> <ip>

  N0S - ABRE-LATAS PARA O SAGEMCOM F@ST5657GF
  PS: ESTA FERRAMENTA EM NADA ESTÁ ASSOCIADA AO GRUPO NOS, O UTILIZADOR É RESPONSÁVEL PELA SUA UTILIZAÇÃO!
  IMPORTANTE: O ROUTER TEM DE ESTAR COM AS CREDÊNCIAIS ORIGINAIS (admin/admin), CASO CONTRÁRIO NÃO FUNCIONARÁ!

Exemplo:
  $ n0s -t <ip>
  $ n0s -a <ip>

Opções:
  -t   --testar          Verifica se é possível o jailbreak
  -a   --abrir           Faz o jailbreak ao router
  -v   --version         Mostra a versão da app
  -h   --help            Mostra a ajuda 
 ```

### Download:

Windows x64 [Download](https://github.com/n0sp0is/n0s/releases/download/master/n0s_win64.exe)

Linux x64 [Download](https://github.com/n0sp0is/n0s/releases/download/master/n0s_linux_x64)

MacOS [Download](https://github.com/n0sp0is/n0s/releases/download/master/n0s_mac)
