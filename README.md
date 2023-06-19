# EFI-ASUSH110MC-BR-HACKINTOSH
EFI HACKINTOSH pronta para placa mãe ASUS H110M C/BR equipada com Intel de 7th gen, apenas iGPU.

Esta EFI foi gerada usando o OpenCore 0.9.2, seguindo o guia em vídeo feito pelo Gabriel Kuchina,
os arquivos utilizados foram adquiridos no repositório do mesmo seguindo a compatibilidade com o meu dispositivo no caso:
Placa-mãe ASUS H110M-C/BR, equipada com Intel Core i5 7400 (4/4, 3,00GHz), 16GB DDR4, apenas GPU Integrada (Intel HD Graphics 630). Tudo funciona como deveria, inclusive a aceleração gráfica.

A mídia de instalação do MacOS utilizada foi o MacOS Big Sur.
EFI completamente funcional pra quem apenas deseja usar a iGPU. Se você quer usar uma GPU externa, deverá gerar gerar sua SMBIOS de acordo com a indicada no repositório da 7th do Gabriel, que é o iMac18,3.

O repositório onde gerei a EFI está neste link:
https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-7THGEN-KABY-LAKE

Agradecimentos: Gabriel Luchina, o maior nome do Hackintosh e o mais confiável atualmente.

PS: no boot-args, adicione o argumento alcid=1 para habilitar o áudio do seu hackintosh. Se não funcionar, você pode resolver baixando a kext deste link: https://github.com/acidanthera/AppleALC/releases/download/1.8.3/AppleALC-1.8.3-RELEASE.zip > substitua a kext na pasta OC, use o propertree para efetuar o OC clean snapshot, salve, reinicie o computador e veja se o áudio está on.
