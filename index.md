## Conteúdo

### 1. [Introdução](pages/1-introducao.md)

* [O que é o shell](pages/o_que_e_o_shell.md)
* [O Bash](pages/o_bash.md)
* [Outros shells](pages/outros_shells.md)
* [Padrões POSIX](pages/padroes_posix.md)
* [Bash/shell scripts](pages/bash_shell_scripts.md)
* [Subshells](pages/subshells.md)

### 2. [Comandos internos herdados](pages/2-comandos_internos_herdados.md)

* [. (ponto)](pages/ponto.md)
* [: (dois pontos)](pages/dois_pontos.md)
* [break](pages/break.md)
* [cd](pages/cd.md)
* [continue](pages/continue.md)
* [eval](pages/eval.md)
* [exec](pages/exec.md)
* [exit](pages/exit.md)
* [export](pages/export.md)
* [getopts](pages/getopts.md)
* [hash](pages/hash.md)
* [pwd](pages/pwd.md)
* [readonly](pages/readonly.md)
* [return](pages/return.md)
* [shift](pages/shift.md)
* [test ou \[ expressão \]](pages/test.md)
* [times](pages/times.md)
* [trap](pages/trap.md)
* [umask](pages/umask.md)
* [unset](pages/unset.md)

### [3. Comandos internos do Bash](pages/3-comandos_internos_do_bash.md)

* [alias](pages/alias.md)
* [bind](pages/bind.md)
* [builtin](pages/builtin.md)
* [caller](pages/caller.md)
* [command](pages/command.md)
* [declare](pages/declare.md)
* [echo](pages/echo.md)
* [enable](pages/enable.md)
* [help](pages/help.md)
* [let](pages/let.md)
* [local](pages/let.md)
* [logout](pages/logout.md)
* [mapfile](pages/mapfile.md)
* [printf](pages/printf.md)
* [read](pages/read.md)
* [readarray](pages/readarray.md)
* [source](pages/source.md)
* [type](pages/type.md)
* [typeset](pages/typeset.md)
* [ulimit](pages/ulimit.md)
* [unalias](pages/unalias.md)

### [4. Modificando o comportamento do shell](pages/4-modificando_o_comportamento_do_shell.md)

* [O comando set](pages/comando_set.md)
* [O comando shopt](pages/comando_shopt.md)

### [5. Variáveis](pages/5-variaveis.md)

* [Variáveis herdadas](pages/variaveis_herdadas.md)
* [Variáveis do Bash](pages/variaveis_do_bash.md)
* [Criando e acessando variáveis](pages/criando_e_acessando_variaveis.md)
* [Variáveis especiais](pages/variaveis_especiais.md)
* [Arrays](pages/arrays.md)

### [6. Expansões](pages/6-expansoes.md)

* [Expansão de diretórios](pages/expansao_de_diretorios.md)
* [Expansão de nomes de arquivos](pages/expansao_de_nomes_de_arquivos.md)
* [Expansão de chaves](pages/expansao_de_chaves.md)
* [Expansão aritmética](pages/expansao_aritmetica.md)
* [Substituição de comando](pages/substituicao_de_comando.md)
* [Substituição de processo](pages/substituicao_de_processo.md)
* [Expansão de parâmetros](pages/expansao_de_parametros.md)

### [7. Aspas](pages/7-aspas.md)

* [Aspas duplas](pages/aspas_duplas.md)
* [Aspas simples](pages/aspas_simples.md)
* [Aspas simples com cifrão ($'...')](pages/aspas_simples_com_cifrao.md)

### [8. Comandos compostos](pages/8-comandos_compostos.md)

* [Estruturas de decisão](pages/estruturas_de_decisao.md)
  * [if, elif, else](pages/if_elif_else.md)
  * [case](pages/case.md)
* [Estruturas de repetição (loops)](pages/estruturas_de_repeticao.md)
  * [O loop for](pages/loop_for.md)
  * [O loop while](pages/loop_while.md)
  * [O loop until](pages/loop_until.md)
  * [O loop select](pages/loop_select.md)
* [Agrupamento de comandos](pages/agrupamento_de_comandos.md)
* [Expressões aritméticas](pages/expressoes_aritmeticas.md)

### [9. Funções](pages/9-funcoes.md)

* [Criando funções](pages/criando_funcoes.md)
* [Passando argumentos para funções](pages/passando_argumentos_para_funcoes.md)
* [Retornando valores](pages/funcoes_retornando_valores.md)
* [Diferenciando funções de comandos com mesmo nome](pages/diferenciando_funcoes_de_comandos_com_mesmo_nome.md)
* [A variável FUNCNAME](pages/a_variavel_funcname.md)

### [10. Redirecionamentos](pages/10-redirecionamentos.md)

* [Descritores de arquivos](pages/descritores_de_arquivos.md)
* [STDIN, STDOUT e STDERR](pages/stdin_stdout_stderr.md)
* [Redirecionamento de entrada](pages/redirecionamento_de_entrada.md)
* [Redirecionamento de saída](pages/redirecionamento_de_saida.md)
* [Redirecionamentos de e para arquivos](pages/redirecionamentos_de_e_para_arquivos.md)
* [Redirecionamento para a saída de erros padrão](pages/redirecionamento_para_a_saida_de_erros_padrao.md)
* ["Here strings"](pages/here_strings.md)
* ["Here documents"](pages/here_documents.md)
* [Duplicando descritores de arquivos](pages/duplicando_descritores_de_arquivos.md)
* [Movendo descritores de arquivos](pages/movendo_descritores_de_arquivos.md)
* [Abrindo descritores de arquivos para leitura e escrita](pages/abrindo_descritores_de_arquivos_para_leitura_e_escrita.md)
* [Pipes](pages/pipes.md)
* [Pipes nomeados](pages/pipes_nomeados.md)

### [11. Expressões Regulares](pages/11-expressoes_regulares.md)

### [12. Ferramentas e Utilitários](pages/12-ferramentas_e_utilitarios.md)

* [awk](pages/awk.md)
* [ed](pages/ed.md)
* [sed](pages/sed.md)
* [tr](pages/tr.md)
* [grep](pages/grep.md)
* [cut](pages/cut.md)
* [cat](pages/cat.md)
* [head](pages/head.md)
* [tail](pages/tail.md)
* [wc](pages/wc.md)
* [bc](pages/bc.md)
* [find](pages/find.md)
* [xargs](pages/xargs.md)

### [13. Casos e soluções (FAQ)](pages/13-casos_e_solucoes.md)

## Ajuda da Wiki

* Guia de Uso
* Sintaxe de Edição
* Sobre o projeto DocLivreBR
* Nossos Colaboradores
* Como colaborar
* Contatos
* Termos de uso

