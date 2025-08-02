# consulta-rapida
Itens de consulta rapida

## Unir particoes PenDrive formatado para Linux

### Usando diskpart no windows
- Abra o prompt de comando como administrador. 
- Digite diskpart e pressione Enter. 
- Digite list disk para ver todos os discos do seu computador, incluindo o pendrive. 
- Identifique o número do seu pendrive e digite select disk N, substituindo "N" pelo número do disco. 
- Digite clean para apagar a partição (atenção: isso apaga todos os dados!). 
- Crie uma nova partição primária com create partition primary. 
- Formate a partição com format fs=ntfs quick ou format fs=fat32 quick, escolhendo o sistema de arquivos desejado. 
- Atribua uma letra à unidade com assign. 
