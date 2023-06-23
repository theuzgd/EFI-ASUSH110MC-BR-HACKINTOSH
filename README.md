# EFI-ASUSH110MC-BR-HACKINTOSH
EFI HACKINTOSH pronta para placa mãe ASUS H110M C/BR equipada com Intel de 7th GEN

SETUP DESTA EFI:
Plataforma: Desktop | Intel 7th GEN
Placa Mãe: Asus H110M-C/BR
Processador: Intel Core i5 7400 3.60GHz
Vídeo: R9 270 2GB GDDR5 | Intel HD Graphics 630
Áudio: Realtek ALC887 Codec
SMBIOS: iMac18,3
macOS: Big Sur
Opencore: 0.9.2

Esta EFI foi gerada usando o OpenCore 0.9.2, seguindo o guia em vídeo feito pelo Gabriel Luchina,
os arquivos utilizados foram adquiridos no repositório do mesmo seguindo a compatibilidade com o meu dispositivo no caso:
Placa-mãe ASUS H110M-C/BR, equipada com Intel Core i5 7400 (4/4, 3,00GHz), 16GB DDR4, apenas GPU Integrada (Intel HD Graphics 630). Tudo funciona como deveria, inclusive a aceleração gráfica.

A mídia de instalação do MacOS utilizada foi o MacOS Big Sur.

O repositório onde gerei a EFI está neste link:
https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-7THGEN-KABY-LAKE

Agradecimentos: Gabriel Luchina, o maior nome do Hackintosh e o mais confiável atualmente.

PS: Se você tiver só o gráfico integrado, gerar a SMBIOS para iMac18,1 e aplicar no config.plist desta EFI.
PS2: As placas de vídeos suportadas serão detectadas sem qualquer patch ou alteração pelo hackintool ou pelo Propertree.
PS3: Kext do codec ALC887 foi atualizada nesta EFI, o parâmetro alcid=1 foi adicionado no config.plist. O áudio da placa-mãe está 100% funcional.
