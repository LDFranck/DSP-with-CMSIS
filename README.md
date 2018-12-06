# Filtro Digital - STM32F446

Como configurar:
> Planejar o filtro no site: http://www.micromodeler.com/dsp/
>> Lembrar de gerar código para ARM CMSIS ("Code Generation" → "ARM+CMSIS");
>
>> Alterar a frequência de amostragem para 200kHz;
>
>> Renomear o filtro como "filter".
>
>> Para Filtros Passa-Alta, substituir o conteúdo do main.c com o conteúdo do main_FPA.c

> Alterar os arquivos "filter.h" e "filter.c" com as configurações geradas pelo site.
