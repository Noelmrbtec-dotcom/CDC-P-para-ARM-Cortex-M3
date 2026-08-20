# CDC-P v3.1 - Um Cyber Organismo com Previsibilidade Absoluta

## Um sistema que transcende a definição de RTOS. Ele respira, tem reflexos, se adapta, se cura, se defende e, se tudo falhar, renasce. Tudo em 1360 palavras de ROM e 80 bytes de RAM.

[![Platform](https://img.shields.io/badge/platform-CORTEX-M3-blue)](https://www.stm.com/en-us/product/STM32F103C8)
[![ROM](https://img.shields.io/badge/ROM-1360%20words%20(66%25)-green)]()
[![RAM](https://img.shields.io/badge/RAM-80%20bytes%20(36%25)-brightgreen)]()
[![Stack](https://img.shields.io/badge/Stack-4%20of%208%20levels-orange)]()
[![Overhead](https://img.shields.io/badge/Overhead-112%C2%B5s%20(1.4%25)-blue)]()
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

---

## Visão Geral

O CDC-P (Concurrency Deterministic Control with Preemption) não é um RTOS tradicional. É um **Cyber Organismo com Previsibilidade Absoluta** — um sistema que exibe funções análogas às biológicas no domínio temporal.

Diferentemente de RTOS preemptivos como FreeRTOS e ThreadX, o CDC-P não usa preempção interruptiva. Em vez disso, respira (tick dinâmico), tem reflexos (URG-S), se adapta ao ambiente (auto-regulagem), se cura de feridas (Task9), se defende de ameaças (Task10 com isolamento permanente) e, se tudo falhar, renasce (reset_cpu). E tudo isso é 100% previsível, 100% determinístico, 100% comprovado em hardware real.

O sistema é imune a condições de corrida, deadlocks e inversão de prioridade por construção arquitetural, não por mecanismos de correção posteriores. Cabe em 1360 palavras de ROM e 80 bytes de RAM em um PIC16F628A de 8 bits com clock de 4 MHz.

> *"A simplicidade é um pré-requisito para a confiabilidade."* — Edsger W. Dijkstra

---

## O Cyber Organismo

| Função Biológica | Equivalente no CDC-P | Mecanismo |
|:---|:---|:---|
| Respiração | Tick dinâmico | Ajusta frequência do sistema conforme a demanda (2ms a 50ms) |
| Reflexos | URG-S | Resposta imediata e involuntária a estímulos externos (mesma iteração) |
| Homeostase | Auto-regulagem | Mantém equilíbrio temporal sob carga variável |
| Cicatrização | Task9 (Síndico) | Recupera tarefas bloqueadas progressivamente |
| Sistema Imunológico | Task10 (Xerife) + pane_taskX | Detecta e isola ameaças permanentemente |
| Renascimento | reset_cpu() | Reinicia o organismo quando tudo falha |
| Evolução | Dimensionamento experimental | Aprende o WCET real de cada tarefa |

**Previsibilidade Absoluta:** Não há "depende". Não há "às vezes". Não há "em algumas condições". Cada função ocorre de forma previsível e reproduzível. Sempre.

---
