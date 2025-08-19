# Sistemas Operacionais — Capítulo 1
**Definições, histórico e visão geral**  
Baseado em: *Modern Operating Systems* (A. S. Tanenbaum & H. Bos)  

> **Notas:** Contextualizar a disciplina, objetivos da aula. Seguiremos a estrutura do Cap. 1 do Tanenbaum & Bos (MOS, 3ª/4ª ed.).

---

## Objetivos da disciplina
- Compreender o papel do SO como interface e gerenciador de recursos
- Conhecer a evolução histórica: batch, multiprogramação, time-sharing, micros, internet
- Introduzir conceitos: processos/threads, memória, E/S, arquivos e chamadas de sistema
- Preparar para aprofundar: escalonamento, sincronização, sistemas de arquivos e segurança

> **Notas:** Relacionar objetivos com a organização do curso. SOM Cap. 1.1–1.2.

---

## Definição de Sistema Operacional
- Programa (ou conjunto de programas) intermediário entre usuário e hardware
- Gerencia recursos: CPU, memória, dispositivos de E/S e armazenamento
- Fornece abstrações: arquivos, processos, sockets, janelas
- Objetivos: facilidade de uso, eficiência e segurança

> **Notas:** Destacar a visão de máquina estendida e gerenciador de recursos. SOM Cap. 1.1.

---

## Visão de um Sistema Computacional
- Consiste em um ou mais processadores, memória principal e secundária (discos), interfaces de rede e dispositivos de entrada e saída (impressoras, teclado, mouse, monitor e etc.)
- É um sistema complexo
- Modo de Linha de Comando (CLI/Shell) e modo Graphical User Interface (GUI)
- Interação via chamadas de sistemas

- https://cambiotraining.github.io/unix-shell/materials/01-basics/01-unix_overview.html#fig-gui-cli
  <img src="[terminal_vs_gui.jpg](https://cambiotraining.github.io/unix-shell/materials/01-basics/01-unix_overview.html#fig-gui-cli)" width="500"  alt="Modo Shell vs Modo GUI">




> **Notas:** Contextualizar hardware e software. SOM Cap. 1.2.

---

## SO: Máquina Estendida e Gerenciador de Recursos
- Máquina estendida: abstrai hardware (arquivos, processos)
- Gerenciador: media acesso a CPU, memória, disco e E/S
- Critérios: desempenho, justiça, política vs. mecanismo

> **Notas:** Explicar exemplos de políticas e mecanismos. SOM Cap. 1.3.

---

## Máquina Multinível (Camadas)
- Aplicativos → Programas de sistema → SO → Linguagem de máquina
- → Microarquitetura → Dispositivos físicos
- Vantagens: portabilidade, manutenção, segurança

> **Notas:** Usar diagrama de camadas. SOM Cap. 1.4.

---

## Componentes de um SO
- Kernel: processos/threads, memória, E/S, sistema de arquivos
- Chamadas de sistema: interface entre apps e kernel
- Drivers e gerenciamento de interrupções
- Interfaces de usuário: CLI e GUI

> **Notas:** Explicar papel das chamadas de sistema. SOM Cap. 1.5.

---

## Modos de Execução e Chamadas de Sistema
- Modo usuário vs. modo kernel
- Chamadas de sistema: transição para o kernel
- Exemplos: open, read, write, fork/exec, socket

> **Notas:** Mostrar fluxo app → syscall → kernel. SOM Cap. 1.5.

---

## Interfaces com o SO
- Textual (CLI/shell)
- Gráfica (GUI)
- APIs e bibliotecas padrão (POSIX, Win32)

> **Notas:** Comparar CLI e GUI. SOM Cap. 1.5.

---

## Formas de Processamento
- Batch (lote)
- Multiprogramação
- Time-sharing

> **Notas:** Comparar throughput x interatividade. SOM Cap. 1.6.

---

## Histórico — 1ª Geração (1945–1955)
- Válvulas (tubos a vácuo)
- Sem SO: programação direta no hardware

> **Notas:** Destacar ausência de SO. SOM Cap. 1.6.

---

## Histórico — 2ª Geração (1955–1965)
- Transistores; Assembly e FORTRAN
- Sistemas de lote (batch), spooling inicial

> **Notas:** Explicar spooling. SOM Cap. 1.6.

---

## Histórico — 3ª Geração (1965–1980)
- Circuitos integrados (SSI/MSI)
- Multiprogramação e time-sharing
- IBM OS/360

> **Notas:** Importância do OS/360. SOM Cap. 1.6.

---

## Histórico — 4ª Geração (1980–1990)
- Alta integração (LSI/VLSI), micros
- MS-DOS, Windows, Mac OS
- Início da Internet

> **Notas:** Popularização do PC. SOM Cap. 1.6.

---

## Histórico — 5ª Geração (1990–Hoje)
- Internet ubíqua; cliente/servidor
- SOs com TCP/IP, multiprocessamento, segurança
- Tempo real, mobile, IoT, CPS

> **Notas:** Conexão com mobilidade. SOM Cap. 1.6–1.7.

---

## Exemplos e Famílias de SO
- Desktop: Windows, macOS, Linux
- Mobile: Android, iOS
- Servidor: Linux, Windows Server, BSDs
- Embarcados: VxWorks, FreeRTOS

> **Notas:** Diferentes requisitos por domínio. SOM Cap. 1.7.

---

## Conclusões
- SO fornece abstrações e gerencia recursos
- História explica decisões de projeto
- Base para próximos temas: processos, escalonamento, memória, E/S

> **Notas:** Reforçar relação teoria-prática.

---

## Bibliografia e Próxima Aula
- Tanenbaum, A. S.; Bos, H. *Modern Operating Systems*
- Silberschatz, A.; Galvin, P.; Gagne, G. *Operating System Concepts*
- Próxima aula: Tipos de SO e Estruturas do Kernel

> **Notas:** Indicar leitura prévia. SOM Cap. 2.
