# AVR
Exemplos de programação para microcontroladores AVR e seus periféricos

# Como compilar os arquivos dos exemplos
Todos os exemplos foram escritos e compilados sem usar nenhuma IDE, assim é possível conhecer melhor todo o processor de compilaçõa dos códigos. O compilador usado foi o AVR-GCC, um compilador de liguagem C/C++ do projeto GNU para microcontroladores AVR. Vou explicar rapidamente alguns comando suficientes para compilar e gerar os arquivos .hex para os exemplos disponíveis aqui, mas uma longa lista de opções estão diponíveis para serem usados com o avr-gcc, uma lista completa é encontrada no site ofcinal do projeto [GNU-GCC](https://gcc.gnu.org/onlinedocs/gcc-7.3.0/gcc/AVR-Options.html#AVR-Options). Um bom tuturial de como instalar as ferramentas de softwares necessárias para rodar os próximos exemplos pode ser encontrado [aqui](http://maxembedded.com/2015/06/setting-up-avr-gcc-toolchain-on-linux-and-mac-os-x/) 


## 
```
avr-gcc -gdwarf-2 -Os -mmcu=atmega8 -c COM-serial.c
```
